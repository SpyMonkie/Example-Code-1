# Example-Code-1
<!DOCTYPE html>
<html>
  <head>
    <link href='https://fonts.googleapis.com/css?family=Roboto:400,300,500,100' rel='stylesheet' type='text/css'>

  </head>
  <body>
    <div class="header">
      <div class="container">
        <h1>Innovation Cloud</h1>
        <p>Connect your ideas globally</p>
        <a class="btn" href="#">Learn More</a>
      </div>
    </div>

    <div class="nav">
      <div class="container">
        <ul>
          <li>Register</li>
          <li>Schedule</li>
          <li>Sponsors</li>
          <li>About</li>
          <li>Contact</li>
        </ul>
      </div>
    </div>

    <div class="main">
      <div class="container">
        <img src="https://s3.amazonaws.com/codecademy-content/projects/innovation-cloud/cloud.svg" height="128" width="196">
        <h2>The Innovation Cloud Conference</h2>
        <p>Connect with the best minds across a wide range of industries to share ideas and brainstorm new solutions to challenging problems.</p>
        <p>Hear industry leaders talk about what worked (and what didn't) so that you can save time on your most challenging projects.</p>
        <p>Learn about the latest research and technologies that you can use immediately to invent the future.</p>
      </div>
    </div>

    <div class="jumbotron">
      <div class="container">
        <h2>Stay Connected</h2>
        <p>Receive weekly insights from industry insiders.</p>
        <a class="btn" href="#">Join</a>
      </div>
    </div>

    <div class="footer">
      <div class="container">
        <p>&copy; Innovation Cloud Conference</p>
      </div>
    </div>
  </body>
</html>
Style.css
html, body {
  margin: 0;
}

h1, h2, a {
  font-family: 'Time Roman Numeral', sans-serif;
  text-transform: uppercase;
}

p {
  font-family: Helvetica, Arial, sans-serif; 
}

.container {
  max-width: 940px;
  margin: 0 auto;
}

/* Main */
.main {
  text-align: center;
  background: url("https://s3.amazonaws.com/codecademy-content/projects/move/bg.jpg") no-repeat center center;
  background-size: cover;
  height: 600px;
}

.main .container {
  position: relative;
  top: 100px;
}

.main h1 {
  color: #00A30B;
  margin: 0;
  font-size: 150px;
}

.main p {
  color: #fff;
  margin: 0 0 20px 0;
  font-size: 18px;
}

.main .btn {
  background-color: #1c1c1c;
  color: #fff;
  font-size: 18px;
  padding: 8px 30px;
  text-decoration: none;
  display: inline-block;
}

/* Supporting */
.supporting {
  background-color: #1c1c1c;
  padding: 50px 0 80px;
  text-align: center;
}

.supporting .col {
  float: left;
  padding: 10px;
  width: 28%;
}

.supporting h2 {
  color: #ffa800;
  font-size: 20px;
  margin-bottom: 10px;
}

.clearfix {
  clear: both;
}

.supporting p {
  color: #efefef;
  font-size: 12px;
  line-height: 20px;
  margin-bottom: 20px;
}

.supporting .btn {
  background-color: #eee;
  color: #1c1c1c;
  font-size: 18px;
  padding: 8px 30px;
  text-decoration: none;
  display: inline-block;
}

/* Feature */
.feature {
  background: url("https://s3.amazonaws.com/codecademy-content/projects/move/feature.jpg") no-repeat center center;
  background-size: cover;
  height: 600px;
  text-align: center;
}

.feature .container {
  position: relative;
  top: 200px;
}

.feature h2 {
  color: #fff;
  font-size: 40px;
  margin:0;
  padding:50px 0 0;
}

/* Footer */
.footer {
  background: url("https://s3.amazonaws.com/codecademy-content/projects/move/footer.jpg") no-repeat center center;
  background-size: cover;
  height: 600px;
  text-align: center;
}

.footer .container {
  position: relative;
  top: 200px;
}

.footer h2 {
  color: #fff;
  font-size: 40px;
  margin: 0 0 20px 0;
  padding:50px 0 0;
}

.footer p {
  color: #fff;
  font-size: 18px;
  margin: 0 0 20px 0;
}

.footer .btn {
  background-color: #1c1c1c;
  color: #fff;
  font-size: 18px;
  padding: 8px 30px;
  text-decoration: none;
  display: inline-block;
}

a.btn:hover {
  background:#ffa800;
  color:#000;
}
index.html
<!DOCTYPE html>
<html>
  <head>
    <link href='https://fonts.googleapis.com/css?family=Oswald:400,700' rel='stylesheet' type='text/css'>
    <link href="/style.css" type="text/css" rel="stylesheet" />
  </head>
  <body>

    <div class="main">
      <div class="container">
        <h1>Move</h1>
        <p>Form healthy habits to take your fitness to the next level.</p>
        <a class="btn" href="#">Start Now</a>
      </div>
    </div>

    <div class="supporting">
      <div class="container">
        <div class="col">
          <h2>Move</h2>
          <p>Become more active by tracking your runs, rides, and walks.</p>
        </div>
        <div class="col">
          <h2>Sync</h2>
          <p>Access your activity on your phone, tablet, or computer.</p>
        </div>
        <div class="col">
          <h2>Compete</h2>
          <p>Set personal challenges and see how you rank against your friends.</p>
        </div>
        <div class="clearfix"></div>
      </div>
    </div>

    <div class="feature">
      <div class="container">
        <h2>Move. Rest. Recover. Move.</h2>
      </div>
    </div>

    <div class="supporting">
      <div class="container">
        <h2>Go Premium</h2>
        <p>Receive recommendations based on your activity to level up.</p>
        <a class="btn" href="#">Learn More</a>
      </div>
    </div>

    <div class="footer">
      <div class="container">
        <h2>Stop scrolling. Start moving.</h2>
        <a class="btn" href="#">Start Now</a>
      </div>
    </div>
    
  </body>
</html>
