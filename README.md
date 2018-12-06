# Vamos a desarrollar en python
[un texto](notebook.ipynb)

libro en [nbviewer](https://nbviewer.jupyter.org/github/minder13/minder/blob/master/notebook.ipynb)

#en python promp jupyter nbconvert --to html notebook.ipynb

[otro texto1](/notebook.html)




<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>


<div class="container">
  <h2>Mi primer dashboard</h2>
  <p>Este es un ejemplo de un panel="pill"</p>
  <ul class="nav nav-pills">
    <li class="active"><a data-toggle="pill" href="#menu1">1</a></li>
    <li><a data-toggle="pill" href="#menu2">2</a></li>
    <li><a data-toggle="pill" href="#menu3">3</a></li>
    <li><a data-toggle="pill" href="#menu4">4</a></li>
  </ul>
  
  <div class="tab-content">
    <div id="menu1" class="tab-pane fade in active">
      <h3>TEXTO INICIAL</h3>
      <p>Este es el texto del primer menu</p>
    </div>
    <div id="menu2" class="tab-pane fade">
      <p>Grafica de Sin(x).</p>
      <img src="img/fig1.png" alt="Sin(x)">
    </div>
    <div id="menu3" class="tab-pane fade">
      <p>Grafica de cosn(x).</p>
      <img src="img/fig3.png" alt="cos(x)">
    </div>
    <div id="menu4" class="tab-pane fade">
      <p>Grafica de cosn(x).</p>
      <img src="img/fig4.png" alt="cos(x)">
    </div>
    
  </div>
</div>


</body>
</html>
