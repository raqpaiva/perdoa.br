<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>💌</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #fff;
      font-family: Arial;
      text-align: center;
      cursor: pointer;
    }
    #msg {
      display: none;
      font-size: 24px;
      max-width: 600px;
    }
  </style>
</head>
<body onclick="mostrar()">

  <div id="msg">
    ME DESCULPA. VOCÊ É O AMOR DA MINHA VIDA E A COISA MAIS IMPORTANTE DO MEU MUNDO. EU TE AMO.<br><br>
    Ass: vida.
  </div>

  <script>
    function mostrar() {
      document.getElementById("msg").style.display = "block";
    }
  </script>

</body>
</html>
