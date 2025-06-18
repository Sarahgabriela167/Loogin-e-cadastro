<!DOCTYPE html>
<html lang="Pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loggin e cadastro</title>
    <form>
    </li>
  <li class="nav-item" role="presentation">
    <button class="nav-link rounded-5" id="profile-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="false">Mercado livre</button>

  </li>
   <main>
  </style>
  </h1>Bem-vindo ao nosso site!</h1>
    <p>Conteúdo da nossa loja aqui.</p>
     <main>

  </main>
  <footer>
    <h2>CADASTRO:</h2>
</ul>
  </li>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email </label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
      <div id="emailHelp" class="form-text">Coloque aqui seu email:</div>
  </div>
  </div>

  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Senha</label>

    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>
  
    <input type="checkbox" class="form-check-input" id="exampleCheck1">

    <label class="form-check-label" for="exampleCheck1">Não lebra senha?</label>

  </div>

    <img src="gmail-logo-2020-01-4d7e53f1-370x175.png" alt="email">
 <button type="submit" class="btn btn-primary">Confirme seu email</button>
     <p>Se você tiver dúvidas sobre nosso site, entre em contato pelo e-mail:</p>
    <h2>Contatos</h2>
    <p><strong>Telefone:</strong> (11) 99999-9999</p>
    <p><strong>Email:</strong> <a href="mailto:suporte@exemplo.com">suporte@exemplo.com</a></p>
    <p><strong>Assunto:</strong> Sobre a conta</p
      css
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }
    header {
      background-color: #ffe600;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      color: #333;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .busca input {
      padding: 5px;
      width: 200px;
    }
    .banner img {
      width: 100%;
      height: auto;
    }
    .categorias, .produtos, .contato, .formulario {
      padding: 20px;
    }
    .produtos-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }
    .produto {
      background-color: white;
      padding: 10px;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .produto img {
      width: 100%;
      height: 100px;
      object-fit: cover;
      border-radius: 4px;
    }
    form input, form button {
      width: 100%;
      padding: 10px;
      margin: 5px 0;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
    }
    a.botao {
      display: inline-block;
      background-color: #3483fa;
      color: white;
      padding: 8px 12px;
      text-decoration: none;
      border-radius: 4px;
      margin-top: 5px;
    }
    a.botao:hover {
      background-color: #1d66d0;
    }


    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }
    header {
      background-color: #ffe600;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      color: #333;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .busca input {
      padding: 5px;
      width: 200px;
    }
    .banner img {
      width: 100%;
      height: auto;
    }
    .categorias, .produtos, .contato, .formulario {
      padding: 20px;
    }
    .produtos-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }
    .produto {
      background-color: white;
      padding: 10px;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .produto img {
      width: 100%;
      height: 80px; /* <-- Imagem menor */
      object-fit: cover;
      border-radius: 4px;
    }
    form input, form button {
      width: 100%;
      padding: 10px;
      margin: 5px 0;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
    }
    a.botao {
      display: inline-block;
      background-color: #3483fa;
      color: white;
      padding: 8px 12px;
      text-decoration: none;
      border-radius: 4px;
      margin-top: 5px;
    }
    a.botao:hover {
      background-color: #1d66d0;
    }
     body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }
    header {
      background-color: #ffe600;
      padding: 15px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    header h1 {
      margin: 0;
      color: #333;
      font-size: 28px;
    }
    .busca input {
      padding: 10px;
      width: 60%;
      max-width: 500px;
      border: 1px solid #ccc;
      border-radius: 5px;
      margin-top: 10px;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .banner img {
      width: 100%;
      height: auto;
    }
    .categorias, .produtos, .contato, .formulario {
      padding: 20px;
    }
    .produtos-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 15px;
    }
    .produto {
      background-color: white;
      padding: 10px;
      border-radius: 6px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .produto img {
      width: 100%;
      height: 80px;
      object-fit: cover;
      border-radius: 4px;
    }
    form input, form button {
      width: 100%;
      padding: 10px;
      margin: 5px 0;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
    }
    a.botao {
      display: inline-block;
      background-color: #3483fa;
      color: white;
      padding: 8px 12px;
      text-decoration: none;
      border-radius: 4px;
      margin-top: 5px;
    }
    a.botao:hover {
      background-color: #1d66d0;
    }
    ody {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #ffe600; /* Amarelo Mercado Livre */
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .logo {
      height: 40px;
    }

    .search-bar {
      flex-grow: 1;
      margin: 0 20px;
    }

    .search-bar input {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
    }

    .menu {
      display: flex;
      gap: 15px;
      align-items: center;
    }

    .menu a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }

    /* Responsividade opcional */
    @media (max-width: 600px) {
      .search-bar {
        display: none;
      }
       body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #ffe600; /* Amarelo Mercado Livre */
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 8px 16px;
      height: 56px;
    }

    .logo {
      width: 134px;
      height: 34px;
      object-fit: contain;
    }

    .search-bar {
      flex: 1;
      margin: 0 20px;
      max-width: 600px;
    }

    .search-bar input {
      width: 100%;
      height: 36px;
      padding: 0 12px;
      font-size: 14px;
      border: none;
      border-radius: 2px;
    }

    .menu {
      display: flex;
      align-items: center;
      gap: 16px;
    }

    .menu a {
      text-decoration: none;
      color: #333;
      font-size: 14px;
      font-weight: 500;
    }

    @media (max-width: 768px) {
      .search-bar {
        display: none;
      }
    }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #fff159;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    .logo {
      font-weight: bold;
      font-size: 20px;
    }

    .search-bar {
      flex: 1;
      margin: 0 20px;
    }

    .search-bar input {
      width: 100%;
      padding: 8px 12px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
    }

    .menu {
      display: flex;
      gap: 15px;
      font-size: 14px;
    }

    .menu a {
      text-decoration: none;
      color: black;
    }

    .menu a:hover {
      text-decoration: underline;
    }
     body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #fff159;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    .logo {
      font-weight: bold;
      font-size: 20px;
    }

    .search-bar {
      flex: 1;
      margin: 0 20px;
    }

    .search-bar input {
      width: 100%;
      padding: 8px 12px;
      border: none;
      border-radius: 4px;
      font-size: 16px;
    }

    .menu {
      display: flex;
      gap: 10px;
    }

    .menu a {
      display: inline-block;
      background-color: white;
      color: black;
      padding: 10px 15px;
      text-align: center;
      text-decoration: none;
      border: 2px solid transparent;
      border-radius: 4px;
      font-size: 14px;
      transition: 0.2s;
    }

    .menu a:hover {
      border: 2px solid #333;
      background-color: #f7f7f7;
    }
 body {
            font-family: Arial, sans-serif;
            padding: 20px;
            background-color: #f5f5f5;
        }
        .container-produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .produto {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        .produto img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .botao {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 15px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .avaliacao {
            color: #fbc02d;
            font-size: 14px;
            margin-top: 5px;
        }
           {
            margin: 8px 0;
           }
        
 
  </footer>
</style>

    
</body>
</html>
