<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Google</title>
    <link rel="shortcut icon" href="img/favicon.ico">
    <!--Font Icon-->
    <link rel="stylesheet" href="https://cdn.linearicons.com/free/1.0.0/icon-font.min.css">
    <!--CSS-->
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <nav id="navbar">
            <ul class="nav-list" id="social-bar">
                <li><a href="#">Gmail</a></li>
                <li><a href="#">Imagens</a></li>
                <li>
                    <a href="#"><span class="lnr lnr-list"></span></a>   
                <li>
                <li><a href="#">Fazer login</a></li>   
            </ul>
        </nav>
    </header>
    <main id="bory">
       <img src="img/google_logo.png" id="google-logo" alt="Google Logo">
       <form action="">
        <div id="input-box">
            <input type="text" id="search-input" name="search">
            <spam class="lnr lnr-magnifier" id="search-icon"></spam>
            <spam class="lnr lnr-keyboard" id="keyboard-icon"></spam>
            <spam class="lnr lnr-mic" id="mic-icon"></spam> 
        </div>
        <div>
            <input type="submit" name="btn-search" value="Pesquisa Google ">
            <input type="submit" name="btn-luck" value="Estou com Sorte">
        </div>
       </form>
    </main>
    <footer>
      <ul id="left-bar" class="nav-list">
        <li><a href="#">Publicidade</a></li>
        <li><a href="#">Negócios</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Como funciona a Pesquisa</a></li>
      </ul>
      <ul id="right-bar" class="nav-list">
        <li><a href="#">Privacidade</a></li>
        <li><a href="#">Termos</a></li>
        <li><a href="#">Configurações</a></li>
      </ul>  
    </footer>  
</body>
</html>

_____________________________________________________________________________________________________________________________________________________________________

/* Geral */ 

bory {
    font-family: Arial, sans-serif;
    font-size: 13px;
    margin: 0;
}

/* Barra de navegação*/

#navbar {
    margin-top: 20px;
}

.nav-list {
    padding: 0 25px;
}

.nav-list li {
    display: inline-block;
    list-style: none;
    padding: 5px 10px;
}

.nav-list li a {
    color: #5f6368;
    text-decoration: none;
}

.nav-list li a:hover {
    text-decoration: underline;
}

#social-bar {
    text-align: right;
}

/* Corpo do Site*/

#bory {
    text-align: center;
}

#google-logo {
    padding-top: 7%;
    margin-bottom: 25px;
}

#input-box {
    width: 43vw; /* viw width*/
    height: 60px;
    position: relative;
    margin-left: auto;
    margin-right: auto;
}

#search-input {
    height: 48px;
    border-radius: 24px;
    width: 100%;
    box-sizing: border-box;
    font-size: 16px;
    padding: 0 50px;
    border: 1px solid #dfdfdf;
    box-shadow: 0px 0px 5px #ddd ;
}

#search-icon, #keyboard-icon, #mic-icon {
    position: absolute;
    top: 15px;
    font-size: 18px;
}

#search-icon {
    left: 20px;
}

#keyboard-icon {
    right: 55px;
}

#mic-icon {
    right: 20px;
}

#bory input[type="submit"] {
    background-color: #f2f2f2;
    border: 1px solid #f2f2f2;
    border-radius: 4px;
    color: #5f6368;
    height: 34px;
    padding: 0 16px;
    font-size: 14px;
    margin: 15px 5px;
    cursor: pointer;
}

#bory input[type="submit"]:hover {
    color: #333;
    border-color: #333;
}

/* Footer - rodapé */

footer {
    position: absolute;
    display: block;
    box-sizing: border-box;
    bottom: 0;
    height: 42px;
    width: 100%;
    background-color: #f2f2f2;
    border-top: 1px solid #e4e4e4;
}

#left-bar, #right-bar {
    display: inline-block;
    margin-top: 8px;
    margin-bottom: 0;
}

#right-bar {
    position: absolute;
    right: 0;
}
