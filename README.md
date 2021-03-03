# starolchen.github.io
<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="utf-8" />
      <title>The Cat House</title>
    <link rel="stylesheet" type="text/css" href="midterm.css" />
  </head>

  <body>
    <header id="header">
      <div class="page-wrapper">
        <div id="slogan">
          <h2><span id="cat-face">(^._.^)</span>The cat house</h2>
        </div>
        <nav id="main-menu">
          <h3 class="hidden">Main menu</h3>
          <ul>
            <li><a href="midterm.html">Home</a></li>
            <li><a href="#">Breeds</a></li>
            <li><a href="#">Articles</a></li>
            <li><a href="#">Adopt</a></li>
            <li><a href="#">About</a></li>
          </ul>
        </nav>
        <div id="banner">
          <div class="banner-content">
            <div class="page-wrapper">
              <h1 class="banner-title">Hello, there!</h1>
              <img class="banner-img" src="cat-black_cropped.png" alt="Black cat eyes" />
              </div>
            </div>
          </div>
      </div> <!-- end page wrapper -->
    </header>

    <div class="page-wrapper">
      <main id="main">
          <div id="account">
            <h3>Interested about cat?</h3>
            <p>Well, you've come to the right place. Explore, <a href="#">learn</a>, have fun!</p>
            <p>Join the community.</p>
            <form action="#">
              <button class="button1">Create an account now</button>
            </form>
          </div>
          <div id="info">
            <h3>Learn about cat</h3>
              <div id="left-side">
                <p><a href="#">Breeds</a></p>
                <img src="norwegian-cat.jpg" alt="Norwgian cat" />
                <p>Learn about different cat breeds.</p>
                <form action="#">
                  <button class="button2">Read about breeds</button>
                </form>
              </div>
              <div id="right-side">
                <p><a href="#">Find a cat</a></p>
                <img src="kitten.jpg" alt="a kitten" />
                <p>Help a cat find a home.</p>
                <form action="#">
                  <button class="button2">Adopt a cat</button>
                </form>
              </div>
          </div>
          <div id="subscribe">
            <form id="user-info">
              <h3>Stay up to date</h3>
              <p>Get the lastest cat-related and tips about by subscribing to our newsletters</p>
              <div class="user-input">
                <div>
                  <label for="username">Name</label>
                  <input type="text" id="username" name="username" placeholder="John Smith">
                </div>
                <div>
                  <label for="username">Email</label>
                  <input type="text" id="email" name="email" placeholder="john.smith@example.com">
                </div>
              </div>
              <div>
                <fieldset id="tips">
                  <legend>Get tips related to</legend>
                  <div class="checkboxes">
                    <input type="checkbox" id="adopt-box" name="adopt-box" value="a">
                    <label for="adopt-box">Cat adoption</label>
                    <input type="checkbox" id="toys-box" name="toys-box" value="t">
                    <label for="toys-box">Cat toys</label>
                    <input type="checkbox" id="care-box" name="care-box" value="c">
                    <label for="care-box">Cat care</label>
                  </div>
                </fieldset>
              </div>
              <div><button class="button3" type="submit" id="register" name="register">Subscribe now</button></div>
            </form>
          </div>
        </main>
      </div>
    <footer id="footer">
      <div id="menu-wrapper" class="page-wrapper">
      <nav id="sub-menu">
        <h3 class="hidden">Sub navigation</h3>
        <ul class="main-subnav">
          <li><a href="#">Breeds</a></li>
          <li><a href="#">Adopt</a></li>
          <li><a href="#">About</a></li>
          <li><a href="#">Legal</a></li>
        </ul>
        <ul>
          <li><a href="#">Search by name</a></li>
          <li><a href="#">How to adopt</a></li>
          <li> </li>
          <li><a href="#">Term and conditions</a></li>
        </ul>
        <ul>
          <li><a href="#">Search by charateristic</a></li>
          <li><a href="#">Find a cat today</a></li>
          <li> </li>
          <li><a href="#">Private policy</a></li>
        </ul>
      </nav>
        <div id="copyright">
          <p>&copy;Copyright The Cat House,2021. All right reserved. This is a fake website for HTTP5104.</p>
        </div>
      </div>
    </footer>
  </body>
</html>
