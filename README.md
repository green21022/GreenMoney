# GreenMoney
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Earnify - Task-Based Earning Platform</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background: #6f42c1;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
    }
    #hero {
      padding: 2rem;
      background: #e9ecef;
      text-align: center;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #6f42c1;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    section {
      padding: 2rem;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #6f42c1;
      color: white;
    }
    ul {
      list-style-type: disc;
      padding-left: 20px;
    }
    form {
      max-width: 400px;
      margin: 0 auto;
      background: #fff;
      padding: 1rem;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    form input[type="text"],
    form input[type="email"],
    form input[type="password"] {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form input[type="submit"] {
      background: #6f42c1;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
      section {
        padding: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Earnify</h1>
    <nav>
      <a href="#tasks">Tasks</a>
      <a href="#rewards">Rewards</a>
      <a href="#login">Login</a>
      <a href="#signup">Sign Up</a>
    </nav>
  </
