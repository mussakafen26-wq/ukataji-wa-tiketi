<!DOCTYPE html>
<html>
<head>
  <title>Dropdown Navigation Example</title>
  <style>
    /* Mwili mzima wa ukurasa (background na maandishi) */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
    }

    /* Nav bar (eneo la juu lenye menu) */
    .navbar {
      background-color: #333;
      overflow: hidden;
    }

    /* Links (menu za juu) */
    .navbar a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 20px;
      text-decoration: none;
    }

    /* Hover effect kwa links */
    .navbar a:hover {
      background-color: #ddd;
      color: black;
    }

    /* Dropdown container */
    .dropdown {
      float: left;
      overflow: hidden;
    }

    /* Button ya dropdown */
    .dropdown .dropbtn {
      font-size: 16px;    
      border: none;
      outline: none;
      color: white;
      padding: 14px 20px;
      background-color: inherit;
      font-family: inherit;
      margin: 0;
    }

    /* Content ya dropdown (links zitakazojificha) */
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #f9f9f9;
      min-width: 160px;
      box-shadow: 0px 8px 16px rgba(0,0,0,0.2);
      z-index: 1;
    }

    /* Links ndani ya dropdown */
    .dropdown-content a {
      float: none;
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
      text-align: left;
    }

    /* Hover effect kwa links za ndani ya dropdown */
    .dropdown-content a:hover {
      background-color: #ddd;
    }

    /* Onyesha dropdown wakati mouse ipo juu */
    .dropdown:hover .dropdown-content {
      display: block;
    }
  </style>
</head>
<body>

  <!-- Nav bar -->
  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    
    <!-- Dropdown moja -->
    <div class="dropdown">
      <button class="dropbtn">Services ▼</button>
      <div class="dropdown-content">
        <a href="#web">Web Design</a>
        <a href="#graphic">Graphic Design</a>
        <a href="#seo">SEO</a>
      </div>
    </div> 

    <a href="#contact">Contact</a>
  </div>

</body>
</html>