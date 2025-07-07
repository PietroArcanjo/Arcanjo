Meu Curriculo 
Arcanjo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1.0" />
  <title>Meu Currículo – [Seu Nome]</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <style>
    body { font-family: sans-serif; }
    .hero { padding: 100px 0; text-align: center; background: #f8f9fa; }
    .section-title { font-weight: 600; margin-bottom: 40px; }
  </style>
</head>
<body>

  <header class="bg-white shadow-sm py-3 fixed-top">
    <div class="container d-flex justify-content-between align-items-center">
      <h1 class="h4 m-0">[Seu Nome]</h1>
      <nav>
        <a href="#sobre" class="mx-2">Sobre</a>
        <a href="#experiencia" class="mx-2">Experiência</a>
        <a href="#educacao" class="mx-2">Educação</a>
        <a href="#contato" class="mx-2">Contato</a>
      </nav>
    </div>
  </header>

  <main class="mt-5 pt-5">
    <section id="sobre" class="hero">
      <img src="sua-foto.jpg" alt="Você" class="rounded-circle mb-3" width="150">
      <h2>Olá, sou [Seu Nome]</h2>
      <p>Desenvolvedor(a) Front‑end com foco em criação de experiências web modernas.</p>
    </section>

    <section id="experiencia" class="container py-5">
      <h2 class="section-title">Experiência</h2>
      <div class="timeline">
        <!-- Exemplo de timeline ou lista -->
        <div class="mb-4">
          <h5>Empresa X – Cargo</h5>
          <small class="text-muted">Jan 2023 – Atual</small>
          <p>Responsabilidades e resultados...</p>
        </div>
      </div>
    </section>

    <section id="educacao" class="container py-5 bg-light">
      <h2 class="section-title">Educação</h2>
      <p><strong>Universidade Y</strong> – Bacharelado em Ciência da Computação (2020‑2024)</p>
    </section>

    <section id="contato" class="container py-5">
      <h2 class="section-title">Contato</h2>
      <form>
        <div class="mb-3"><input type="text" class="form-control" placeholder="Nome"></div>
        <div class="mb-3"><input type="email" class="form-control" placeholder="E‑mail"></div>
        <div class="mb-3"><textarea class="form-control" rows="4" placeholder="Mensagem"></textarea></div>
        <button class="btn btn-primary">Enviar</button>
      </form>
    </section>
  </main>

  <footer class="text-center py-3 bg-white border-top">
    © 2025 [Seu Nome]
  </footer>

</body>
</html>
