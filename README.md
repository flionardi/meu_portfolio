
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Página Web Responsiva</title>
  
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  
</head>
<body>

  
  <header class="bg-dark text-white py-4">
    <div class="container">
      <h1>Página Web Responsiva</h1>
      <nav>
        <ul class="list-inline">
          <li class="list-inline-item"><a href="#">Início</a></li>
          <li class="list-inline-item"><a href="#">Sobre</a></li>
          <li class="list-inline-item"><a href="#">Contato</a></li>
        </ul>
      </nav>
    </div>
  </header>

  
  <section class="py-4">
    <div class="container">
      <h2>Matéria</h2>
      <p>Desenvolvimento FrontEnd.</p>
    </div>
  </section>

  <section class="bg-light py-4">
    <div class="container">
      <h2>Curso</h2>
      <p>Analise e desenvolvimento de sistemas.</p>
    </div>
  </section>

  <section class="py-4">
    <div class="container">
      <h2>Atividade Prática 10 </h2>
      <p>Containers com BootStrap</p>
    </div>
  </section>

  
  <footer class="bg-dark text-white py-4">
    <div class="container">
      <p>&copy; <span id="year"></span> Minha Página Web Responsiva</p>
    </div>
  </footer>

  
  <script>
    
    document.getElementById("year").innerText = new Date().getFullYear();
  </script>

</body>
</html>
