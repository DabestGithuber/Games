<!DOCTYPE html>
<html lang="en">

<head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
</head>

<body>

    <div class="container">

        <section id="app">
            <h1>Apps</h1>
            <div class="line"></div>
            <iframe width="400" height="620" style="border: 0px;" src="https://studio.code.org/projects/applab/TnYBodnn3x0rNhYb4J9J-hZPjzgOqIRDG7vkSP2WJCI/embed"></iframe>
            <iframe width="400" height="620" style="border: 0px;" src="https://studio.code.org/projects/applab/bpWFoLtwz3JGl9i2jM7xajXQLN8pCbMEekad-4FAscI/embed"></iframe>
        </section>



        <h2>Click On The Games To Explore</h2>

        <h5>This games are bulid in game lab, click on the game to play</h5>

        <div id="myCarousel" class="carousel slide">
            <center>
                
                <div class="carousel-inner">
                    <div class="item active">
                        <a href="https://studio.code.org/projects/gamelab/Sdt_OgR8VajkwZ9t45UeVtzMLGiyqhNFJexB9eCe480" target="_blank">
                            <img src="game1.png">
                        </a>
                        <p>Car Racing</p>
                    </div>

                    <div class="item">
                        <a href="https://studio.code.org/projects/gamelab/N25kriFEAiBTZwfbYpDjc_qryNjSBhYW-3fOuYRt_SI" target="_blank">
                            <img src="game2.png">
                        </a>
                        <p>Be in space</p>
                    </div>

                    <div class="item">
                        <a href="https://studio.code.org/projects/playlab/Xoq31TZJRl0W9K95JthlADu6tbI1xGTsVHpOvYsNtuE" target="_blank">
                            
                            <img src="game3.PNG">
                        </a>
                        <p>Bird hunting for pie</p>
                    </div>

                    <div class="item">
                        
                        <a href="https://studio.code.org/projects/playlab/WzncdAxXTuhs9JIxkX2v6qScTqL5bBzoUdfsqrxF4fI" target="_blank">
                            <img src="game4.PNG">
                        </a>
                        <p>Password Checker</p>
                    </div>

                </div>

                
                <a class="left carousel-control" href="#myCarousel" data-slide="prev">
                    <span class="glyphicon glyphicon-chevron-left"></span>
                </a>

                <a class="right carousel-control" href="#myCarousel" data-slide="next">
                    
                    <span class="glyphicon glyphicon-chevron-right "></span>
                </a>

            </center>
        </div>

    </div>

</body>

</html>

body
{
    text-align: center;
}
.container{
  background-color: mediumaquamarine;  
}
#app {
    background-color: aliceblue;
}

#myCarousel
{
    background-color: red;
}

#myCarousel img
{
    height: 300px;
    margin-top: 35px;
}

.carousel-inner p
{
    margin-top: 15px;
    color : white;
    font-size: 20px;
}
