# Vamos a desarrollar en python
[un texto](notebook.ipynb)

libro en [nbviewer](https://nbviewer.jupyter.org/github/minder13/minder/blob/master/notebook.ipynb)

#en python promp jupyter nbconvert --to html notebook.ipynb

[otro texto1](/notebook.html)


<!DOCTYPE html>
<html lang="en">
<!-- Esta parte es generica -->
<head>
  <title>Mi primer dashboard (TITULO) </title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
</head>
<body>

<div class="container">
  <h1>Mi primer dashboard usando Boostrap (CONTENEDOR)</h1>
  <p>Este es un parrafo.</p> 

  <div class="row">
    <!--- Columna 1 --->
    <div class="col-sm-4">
      <p>Grafica 1</p>
      <img src="/img/fig1.png" alt="FIG1">    
    </div>
    <!--- Columna 2 --->
    <div class="col-sm-4">
      <p>Grafica 2</p>
      <img src="/img/fig2.png" alt="FIG1">
    </div>
  </div>    
</div>

</body>
</html>
