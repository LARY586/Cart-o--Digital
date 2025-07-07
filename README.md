# Cart-o--Digital
Criada pela aluna Larissa na materia fpw Utilizando apenas HTML e CSS básicos, você deve criar a estrutura e o estilo deste cartão de visita digital.
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cartão de Visita - Larissa</title>
  <link rel="stylesheet" href="style.css">
  <!-- Font Awesome para ícones -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
  <main class="card">
    <header>
      <img src="https://github.com/LARY586/Cart-o--Digital/edit/main/README.md" alt="Foto de perfil de Larissa">
      <h1>Larissa Florentino Dos Santos</h1>
      <h2>Estudante</h2>
    </header>

    <section class="about">
      <p>Estudante comprometida com o aprendizado e o desenvolvimento constante. Interessada em contribuir de forma positiva em tudo o que se propõe a fazer.</p>
    </section>

    <section class="contact">
      <p><i class="fas fa-envelope"></i> larissa.fsantos8@aluno.edu.es.gov.br</p>
      <p><i class="fas fa-phone"></i> (27) 99796-7985</p>
      <p><i class="fas fa-map-marker-alt"></i> Espírito Santo</p>
    </section>

    <footer class="social-links">
      <a href="#" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="#" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
    </footer>
  </main>
</body>
</html>
🎨 style.css
css
Copiar
Editar
/* Reset básico */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  background-color: #eef2f5;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 20px;
}

.card {
  max-width: 400px;
  width: 100%;
  background-color: #ffffff;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  padding: 25px;
  text-align: center;
}

/* Foto de perfil */
header img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 15px;
  border: 3px solid #0077b5;
}

/* Título e subtítulo */
header h1 {
  font-size: 22px;
  color: #333;
  margin-bottom: 5px;
}

header h2 {
  font-size: 16px;
  color: #666;
  margin-bottom: 10px;
}

/* Descrição pessoal */
.about {
  font-size: 14px;
  color: #444;
  margin: 15px 0;
}

/* Contatos */
.contact p {
  font-size: 14px;
  margin: 8px 0;
  color: #333;
}

.contact i {
  margin-right: 8px;
  color: #0077b5;
}

/* Links Sociais */
.social-links {
  margin-top: 15px;
}

.social-links a {
  margin: 0 10px;
  color: #333;
  font-size: 22px;
  transition: transform 0.3s, color 0.3s;
}

.social-links a:hover {
  color: #0077b5;
  transform: scale(1.2);
}
