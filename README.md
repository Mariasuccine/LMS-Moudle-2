# LMS-Moudle-2

<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="stylesheet" type="text/css" href="css/styles.css">
    <title>Module 2 Solution</title>
</head>
<body>

   <style type="text/css"> {
    box-sizing: border-box;
}

h1 {
    font-family: Brushstroke, fantasy;
    color: #000000;
    text-align: center;
}

body {
    background-image: url("background.jpg");
    background-color: #FEF5CA;

}

p {
    padding: 10px;
    margin: 0;
}

.container {
    border: none;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10px;
    margin-bottom: 10px;
    padding: 10px;
}

section {
    border: 1px solid black;
    background-color: #00FF99;
    width: 100%;
    height: 200px;
    font-family: Helvetica;
    color: black;
    position: relative;
    overflow: auto;
}

#chicken {
    border: 1px solid black;
    text-align: center;
    width: 30%;
    margin-left: 70%;
    font-family: Georgia,sans-serif;
    font-weight: bold;
    font-size: 125%;
    margin-bottom: 0;
    margin-top: 0;
    padding: 5px;
    background-color: #FFFF00;
}

#beef {
    border: 1px solid black;
    text-align: center;
    width: 30%;
    margin-left: 70%;
    font-family: Georgia,sans-serif;
    font-weight: bold;
    font-size: 125%;
    margin-bottom: 0;
    margin-top: 0;
    padding: 5px;
    background-color: #FF1439;
}

#sushi {
    border: 1px solid black;
    text-align: center;
    width: 30%;
    margin-left: 70%;
    font-family: Georgia,sans-serif;
    font-weight: bold;
    font-size: 125%;
    margin-bottom: 0;
    margin-top: 0;
    background-color: #6495ED;
    color: white;
    padding: 5px;
}

.row {
    width: 100%;
}

/* Desktop view */

@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }

  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }

}
</style>
    <h1>Our Menu</h1>
    <div class="row">
    <div class="container col-lg-4 col-md-6 col-sm-12">
        <section>
        <div id="chicken">
            Chicken
        </div>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi tristique ipsum sit amet nunc posuere, at dictum massa fermentum. Sed tempor turpis quis dui pharetra, eu suscipit elit cursus. Praesent sed libero turpis. Aliquam varius elit mauris, vestibulum laoreet leo rhoncus ac. Fusce at facilisis velit. Vivamus facilisis semper risus, et efficitur justo suscipit ac. 
        </p>
        </section>
    </div>
    <div class="container col-lg-4 col-md-6 col-sm-12">
        <section>
        <div id="beef">
            Beef
        </div>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi tristique ipsum sit amet nunc posuere, at dictum massa fermentum. Sed tempor turpis quis dui pharetra, eu suscipit elit cursus. Praesent sed libero turpis. Aliquam varius elit mauris, vestibulum laoreet leo rhoncus ac. Fusce at facilisis velit. Vivamus facilisis semper risus, et efficitur justo suscipit ac. 
        </p>
        </section>
    </div>
    <div class="container col-lg-4 col-md-12 col-sm-12">
        <section>
        <div id="sushi">
            Sushi
        </div>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi tristique ipsum sit amet nunc posuere, at dictum massa fermentum. Sed tempor turpis quis dui pharetra, eu suscipit elit cursus. Praesent sed libero turpis. Aliquam varius elit mauris, vestibulum laoreet leo rhoncus ac. Fusce at facilisis velit. Vivamus facilisis semper risus, et efficitur justo suscipit ac. 
        </p>
        </section>
    </div>


    </div>
</body>
</html>
