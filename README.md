<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Login Formulário</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
      body {
        font-family: Arial, sans-serif;
        background-image: linear-gradient(to bottom right, #000000, #ffffff);
      }
      .card {
        background-color: #ffffff;
        border-radius: 10px;
        box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.2);
        padding: 20px;
        width: 90%;
        max-width: 600px;
        margin: 50px auto;
      }
      h2 {
        text-align: center;
        color: #993399;
      }
      input[type=text], input[type=password] {
        width: 100%;
        padding: 12px 20px;
        margin: 8px 0;
        display: inline-block;
        border: 1px solid #ccc;
        box-sizing: border-box;
        border-radius: 5px;
        background-color: #f1f1f1;
        color: #993399;
      }
      button[type=submit] {
        background-color: #993399;
        color: white;
        padding: 14px 20px;
        margin: 8px 0;
        border: none;
        cursor: pointer;
        width: 100%;
        border-radius: 5px;
      }
      button[type=submit]:hover {
        background-color: #732264;
      }
      @media screen and (max-width: 768px) {
        .card {
          width: 100%;
          margin: 20px auto;
        }
      }
    </style>
  </head>
  <body>
    <div class="card">
      <h2>Seja bem-vindo a Mega Store</h2>
      <p>Faça o login para garantir suas compras</p>
      <form action="/login" method="post">
        <div>
          <label for="usuario">Usuário:</label>
          <input type="text" id="usuario" name="usuario" required>
        </div>
        <div>
          <label for="senha">Senha:</label>
          <input type="password" id="senha" name="senha" required>
        </div>
        <button type="submit">Entrar</button>
      </form>
    </div>
    
  </body>
</html>

///site para vendedores que precisam 
///use o app Acode <--
