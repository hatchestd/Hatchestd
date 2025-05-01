* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Helvetica Neue', sans-serif;
}

body {
  background-color: #fdfcfb;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #fff;
  padding: 20px;
  border-bottom: 1px solid #ddd;
  text-align: center;
}

header h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 15px;
}

nav a {
  text-decoration: none;
  color: #444;
  font-weight: bold;
}

.hero {
  background-image: url('coffee.jpg'); /* Add your image path here */
  background-size: cover;
  background-position: center;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: white;
  text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
}

.hero h2 {
  font-size: 2rem;
  text-align: center;
  padding: 0 20px;
}

section {
  padding: 40px 20px;
  text-align: center;
}

footer {
  background-color: #fafafa;
  text-align: center;
  padding: 15px;
  font-size: 0.9rem;
  border-top: 1px solid #ddd;
}
