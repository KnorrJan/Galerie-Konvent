
body {
  margin: 0;
  font-family: 'Roboto', sans-serif;
  background-color: #f5f2ec;
  color: #3b2f2f;
}
header {
  background-color: #5c4432;
  color: #fffbe9;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo {
  font-family: 'Playfair Display', serif;
  font-size: 1.8rem;
}
nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
  margin: 0;
  padding: 0;
}
nav a {
  color: #fffbe9;
  text-decoration: none;
  font-weight: bold;
}
nav a:hover {
  color: #e3c598;
}
section {
  padding: 2rem;
  max-width: 1200px;
  margin: auto;
}
h1, h2 {
  font-family: 'Playfair Display', serif;
  color: #3b2f2f;
}
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}
.product {
  background: #fff;
  padding: 1rem;
  border-radius: 1rem;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}
.product:hover {
  transform: translateY(-5px);
}
.product img {
  width: 100%;
  height: auto;
  border-radius: 0.5rem;
}
.product h3 {
  margin-top: 1rem;
  font-size: 1.25rem;
  color: #3b2f2f;
}
.product p {
  margin: 0.5rem 0;
}
.product button {
  background-color: #5c4432;
  color: white;
  border: none;
  padding: 0.5rem 1rem;
  border-radius: 0.5rem;
  cursor: pointer;
}
.product button:hover {
  background-color: #a97d53;
}
footer {
  background-color: #5c4432;
  color: white;
  text-align: center;
  padding: 1rem;
  margin-top: 2rem;
}
