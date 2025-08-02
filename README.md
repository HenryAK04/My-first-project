body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f2f2f2;
}

header {
  background: #129dba;
  color: white;
  padding: 10px;
  text-align: center;
}

header input {
  margin-top: 10px;
  padding: 8px;
  width: 80%;
  max-width: 400px;
}

nav {
  display: flex;
  justify-content: space-around;
  background: #333;
  padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
}

.products {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  padding: 20px;
}

.product {
  background: white;
  padding: 10px;
  text-align: center;
  border-radius: 5px;
}

.product img {
  width: 100%;
  height: auto;
}

.product button {
  background: #142ddb;
  color: white;
  padding: 8px;
  border: none;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 10px;
  background: #333;
  color: white;
}
