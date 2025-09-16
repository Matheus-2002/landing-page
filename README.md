
index
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Recicle e Transforme o Mundo</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="header">
    <nav class="nav container">
      <a href="index.html" class="logo">♻️ RecicleJá</a>
      <ul class="nav-links">
        <li><a href="index.html" class="active">Início</a></li>
        <li><a href="como-funciona.html">Como funciona</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero container">
      <h1>Vamos juntos cuidar do planeta</h1>
      <p>Reciclar é o primeiro passo para um mundo mais sustentável e saudável para todos.</p>
      <a href="como-funciona.html" class="btn-primary">Saiba como funciona</a>
    </section>

    <section class="info container">
      <div class="card">
        <h2>Por que reciclar?</h2>
        <p>Reduz o lixo no meio ambiente, economiza recursos naturais e ajuda a diminuir a poluição.</p>
      </div>
      <div class="card">
        <h2>O que pode ser reciclado?</h2>
        <p>Papel, plástico, vidro, metal e muitos outros materiais que podem ter uma nova vida.</p>
      </div>
      <div class="card">
        <h2>Como ajudar?</h2>
        <p>Separe o lixo, informe-se sobre pontos de coleta e incentive sua comunidade.</p>
      </div>
    </section>
  </main>

  <footer class="footer">
    <p>© 2025 RecicleJá - Faça parte da mudança</p>
  </footer>
</body>
</html>

como-funciona
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Como funciona a reciclagem</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="header">
    <nav class="nav container">
      <a href="index.html" class="logo">♻️ RecicleJá</a>
      <ul class="nav-links">
        <li><a href="index.html">Início</a></li>
        <li><a href="como-funciona.html" class="active">Como funciona</a></li>
      </ul>
    </nav>
  </header>

  <main class="container">
    <section class="how-it-works">
      <h1>Como funciona a reciclagem?</h1>
      <p>A reciclagem é um processo que transforma materiais usados em novos produtos, reduzindo a extração de recursos naturais e a quantidade de lixo.</p>

      <ol>
        <li><strong>Separação:</strong> Separe os materiais recicláveis do lixo comum.</li>
        <li><strong>Coleta:</strong> Leve até pontos de coleta ou aguarde o recolhimento seletivo.</li>
        <li><strong>Triagem:</strong> Materiais são classificados para o próximo processo.</li>
        <li><strong>Processamento:</strong> Materiais são limpos e transformados em matéria-prima.</li>
        <li><strong>Reutilização:</strong> Matéria-prima é usada para fabricar novos produtos.</li>
      </ol>

      <a href="index.html" class="btn-secondary">Voltar para início</a>
    </section>
  </main>

  <footer class="footer">
    <p>© 2025 RecicleJá - Faça parte da mudança</p>
  </footer>
</body>
</html>



styles
/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: #333;
  background: #f0f9f4;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

/* Header */
.header {
  background-color: #2e7d32;
  color: white;
  padding: 1rem 0;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-weight: bold;
  font-size: 1.5rem;
  text-decoration: none;
  color: white;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  text-decoration: none;
  color: white;
  font-weight: 600;
  transition: color 0.3s;
}

.nav-links a:hover,
.nav-links a.active {
  color: #a5d6a7;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 3rem 1rem;
  background: #81c784;
  color: #1b5e20;
  border-radius: 8px;
  margin-top: 2rem;
}

.hero h1 {
  font-size: 2.8rem;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.btn-primary {
  background-color: #1b5e20;
  color: white;
  padding: 0.75rem 2rem;
  border: none;
  border-radius: 30px;
  font-weight: 700;
  font-size: 1rem;
  cursor: pointer;
  text-decoration: none;
  transition: background-color 0.3s;
}

.btn-primary:hover {
  background-color: #145214;
}

/* Info Section */
.info {
  margin: 3rem 0;
  display: flex;
  gap: 1.5rem;
  justify-content: space-between;
  flex-wrap: wrap;
}

.card {
  background: white;
  flex: 1 1 250px;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-5px);
}

.card h2 {
  color: #2e7d32;
  margin-bottom: 0.75rem;
}

/* Footer */
.footer {
  background-color: #2e7d32;
  color: white;
  text-align: center;
  padding: 1rem 0;
  margin-top: auto;
  font-size: 0.9rem;
}

/* How It Works page */
.how-it-works {
  background: white;
  margin: 3rem 0;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.how-it-works h1 {
  color: #2e7d32;
  margin-bottom: 1rem;
}

.how-it-works ol {
  margin-left: 1.5rem;
  margin-bottom: 2rem;
}

.btn-secondary {
  background-color: #81c784;
  color: #1b5e20;
  padding: 0.75rem 2rem;
  border: none;
  border-radius: 30px;
  font-weight: 700;
  font-size: 1rem;
  cursor: pointer;
  text-decoration: none;
  display: inline-block;
  transition: background-color 0.3s;
}

.btn-secondary:hover {
  background-color: #66bb6a;
}

/* Responsividade */

@media (max-width: 768px) {
  .info {
    flex-direction: column;
  }

  .hero h1 {
    font-size: 2rem;
  }
}

@media (max-width: 480px) {
  .nav-links {
    display: none;
  }

  .hero {
    padding: 2rem 1rem;
  }
}



