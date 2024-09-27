<!DOCTYPE html>
<html>


<head>
  <title>minha pagína pessoal</title>
</head>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;


  }


  body {
    font-family: arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
    padding: 20px;
  }


  header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
  }


  header ul {
    list-style: none;


  }


  nav ul li {
    display: inline;
    margin: 0 10px;
  }


  nav ul li a {
    color: #fff;
    text-decoration: none;
  }


  section {
    margin: 20px 0;
  }


  section#sobre,
  section#projeto,
  section#cadastro,
  section#contato {
    background-color: #FFF;
    padding: 20px;
    border-radius: 20px;
    box_shadow: 0 0 10px rgba(0, 0, 0, 0.1)
  }


  footer {
    text-align: center;
    margin-top: 20px;
  }

  h3 {
    text-align: center;
  }




  form {
    max-width: 400px;
    margin: 20px auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }




  label,
  input {
    display: block;
    margin-bottom: 10px;
  }




  input[type="text"],
  input[type="email"],
  input[type="tel"] {
    width: 95%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }


  input[type="submit"] {
    width: 100%;
    padding: 10px;
    border: none;
    border-radius: 5px;
    background-color: #007bff;
    color: #fff;
    cursor: pointer;
  }




  input[type="submit"]:hover {
    background-color: #0056b3;
  }
</style>




<body>
  <header>
    <h1>Bem vindo a página de Kaue Oliveira Garcia</h1>
    <nav>
      <ul>
        <li><a href="#sobre">sobre mim</a></li>
        <li><a href="#projeto">projetos</a></li>
        <li><a href="#cadastro">Cadastro</a></li>
        <li><a href="#contato">contato</a></li>




      </ul>
    </nav>
  </header>
  <section id="sobre">
    <h2>Sobre mim</h2>
    <p>Sou um estudante da escola Joaquim Amarante, </p>
    <p>Moro em Videira Santa Catarina, tenho 14 anos, </p>
    <p>e gosto de jogar basquete. </p>




  </section>




  <section id="projeto">
    <h2>projetos</h2>
    <ul>
      <li>projeto 1: <a href="#">descrição 1</a></li>
      <li>projeto 2: <a href="#">descrição 2</a></li>
    </ul>
  </section>
  <section id="cadastro">
    <h3>Cadastro De Pessoas</h3>
    <form>
      <label>Nome:</label>
      <input type="text" id="Nome" name="Nome" required>


      <label>Email:</label>
      <input type="Email" id="Email" name="Email" required>


      <label>Telefone:</label>
      <input type="tel" id="Telefone" name="Tefone" required>
      <input type="submit" value="Cadastrar">
    </form>








    </form>
  </section>
  <section id="contato">
    <h2>contato</h2>
    <p>Entre em contato comigo via <a
        href="mailto:kaue_garcia@estudante.sesisenai.org.br">kaue_garcia@estudante.sesisenai.org.br</a></p>
  </section>
  <footer>
    <p>&copy;2024-Kaue Oliveira</p>








</body>




</html>
