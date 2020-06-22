<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      margin: 10;
      font-family: Arial, Helvetica, sans-serif;
    }

    .topnav {
      overflow: hidden;
      background-color: #0000; #menu bar backgound color
    }

    .topnav a {
      float: left;
      color: black; #font color
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
      font-size: 17px;
    }

    .topnav a:hover {
      background-color: #F8C471;
      color: black;
    }

    .topnav a.home {
      background-color: #F9E79F;
      color: black;
    }

    .topnav-right {
      float: right;
    }

    h2, p {
      text-align: center;
    }

    ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      width: 10%; #right side bar width
      background-color: #0000;
      position: fixed;
      height: 100%;
      overflow: auto;
    }

    li a {
      text-align: left;
      display: block;
      color: #000;
      padding: 8px 16px;
      text-decoration: none;
    }

    li a.active {
      background-color: #4CAF50;
      color: white;
    }

    li a:hover:not(.active) {
      background-color: #F7DC6F;
      color: white;
    }

    .dropdown {
      float: left;
      overflow: hidden;
    }

    .dropdown .dropbtn {
      font-size: 16px;
      border: none;
      outline: none;
      color: black;
      padding: 8px 16px;
      background-color: inherit;
      font-family: inherit;
      margin: 0;
    }

    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #FAD7A0;
      min-width: 160px;
      box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
      z-index: 1;
    }

    .dropdown-content a {
      float: none;
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: left;
    }

    .dropdown-content a:hover {
      background-color: red;
    }

    .dropdown:hover .dropdown-content {
      display: block;
    }

    .pictures{
      display: flex;
      text-align: center;
    }

  </style>
</head>

<body>
  <div class="topnav">
    <a class="home" href="#home">RC</a>
    <a href="#myinfo">What's RC</a>
    <a href="#cs">CustomerService</a>
    <div class="topnav-right">
      <!--
      <div class="dropdown">
        <button class="dropdown">Log In</button>
          <div class="dropdown-content">
            <a href="#"> 1</a>
            <a href="#">Link 2</a>
          </div> -->
        <a href="#login">Log In</a>
        <a href="#favorite">Favorite</a>
        <a href="#shoppingbag">Shopping Bag</a>
    </div>
  </div>

  <div style="padding-left:16px">
    <h2>Ran's Closet</h2>
    <p>Choose your Friutes</p>
  </div>

  <div class="leftsidenav">
    <ul>
      <div class="dropdown">
        <button class="dropbtn">Top
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content">
          <a href="#">T-Shirts</a>
          <a href="#">Blouse</a>
          <a href="#">SweatShirts</a>
        </div>
      </div>
      <br>
      <br>
      <li><a href="#dress">Dress</a></li>
      <li><a href="#skirts">Skirts</a></li>
    </ul>
  </div>

  <div class="video">
    <p align="middle">
      <video class ="center" width=50% autoplay muted loop="true">
				<source src="video2.mp4" type="video/mp4">
				Your browser does not support the video tag.
		  </video>
	  </p>
  </div>

  <div class="pictures">
    <div class="picture">
      picture1
      <button class="picture-button">
      Click me
      </button>
    </div>
    <div class="picture">
      picture2
      <button class="picture-button" picture-button--active>
      Click me
      </button>
    </div>
    <div class="picture">
      picture3
      <button class="picture-button" picture-button--active>
      Click me
      </button>
    </div>
  </div>

  </body>
</html>
