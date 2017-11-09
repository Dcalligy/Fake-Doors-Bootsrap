# Fake-Doors-Bootsrap
Website created using a Bootstrap template for my Web Applications class.

Added the carousel below:

```html
<div id = "myCarousel" class="carousel slide" data-ride="carousel">
  <!-- Indicators-->
  <ol class="carousel-indicators">
    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
    <li data-target="#myCarousel" data-slide-to="1"></li>
    <li data-target="#myCarousel" data-slide-to="2"></li>
  </ol>

    <!-- Wrapper for slides-->
    <div class ="carousel-inner">
      <div class="item active">
        <img src="images/fakedoors.jpg" alt="Fake Doors 0" style="width:100%;">
      </div>

      <div class="item">
        <img src="images/fakedoors1.jpg" alt="Fake Doors 1" style="width:100%;">
      </div>

      <div class="item">
        <img src="images/fakedoors7.jpg" alt="Fake Doors 7"style="width:100%;">
      </div>

      <!-- Left and right controls-->
      <a class="left carousel-control" href="#myCarousel" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#myCarousel" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
</div>
```

I also added a popover on the Login button.
```html
<ul class="nav navbar-nav navbar-right">
  <li><a href="#" title="Username" data-toggle="popover" data-placement="bottom" 
         data-content="Login Currently Unavailble"><span class="glyphicon glyphicon-log-in"></span>Login</a></li>
  <script>
    $(document).ready(function(){
      $('[data-toggle="popover"]').popover();
    });
  </script>
</ul>
```
