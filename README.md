# trabalho-matematica-II
HTML: 

```
<!DOCTYPE html>
<html>
  <head>
    <title>Site de Passagens</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <header>
      <h1>Site de Passagens</h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Passagens Aéreas</a></li>
          <li><a href="#">Passagens Rodoviárias</a></li>
          <li><a href="#">Pacotes de Viagem</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <h2>Encontre a sua passagem agora</h2>
      <form>
        <input type="text" placeholder="Origem">
        <input type="text" placeholder="Destino">
        <input type="date" placeholder="Data de partida">
        <input type="date" placeholder="Data de retorno">
        <button type="submit">Buscar</button>
      </form>
      <div class="resultados">
        <h3>Resultados da busca</h3>
        <ul>
          <li>
            <img src="passagem.jpg">
            <h4>Passagem para São Paulo</h4>
            <p>A partir de R$ 200,00</p>
            <button type="button">Comprar</button>
          </li>
          <li>
            <img src="passagem.jpg">
            <h4>Passagem para Rio de Janeiro</h4>
            <p>A partir de R$ 150,00</p>
            <button type="button">Comprar</button>
          </li>
          <li>
            <img src="passagem.jpg">
            <h4>Passagem para Salvador</h4>
            <p>A partir de R$ 300,00</p>
            <button type="button">Comprar</button>
          </li>
        </ul>
      </div>
    </main>
    <footer>
      <p>&copy; 2021 Site de Passagens</p>
    </footer>
  </body>
</html>
```

CSS:

```
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style: none;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

form {
  display: flex;
  flex-wrap: wrap;
}

form input {
  padding: 10px;
  margin-right: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  border: none;
}

form button {
  padding: 10px 20px;
  background-color: #333;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.resultados ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

.resultados li {
  width: 30%;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
  padding: 10px;
}

.resultados li img {
  width: 100%;
  height: auto;
  margin-bottom: 10px;
}

.resultados li h4 {
  margin: 0;
  margin-bottom: 10px;
}

.resultados li p {
  margin: 0;
  margin-bottom: 10px;
  font-weight: bold;
}

.resultados li button {
  padding: 10px 20px;
  background-color: #333;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}
``` 
