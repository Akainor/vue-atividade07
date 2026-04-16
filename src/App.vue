<template>
  <div class="page">
    <header class="header">
      <div class="header-content">
        <img :src="vueLogo" alt="Vue logo" class="logo" />
        <h1>Projeto Vue</h1>
      </div>
    </header>

    <main class="main">
      <section class="content">
        <h2>Links do Projeto</h2>

        <div class="links">
          <a
            href="https://github.com/Akainor/vue-atividade07"
            target="_blank"
            rel="noopener"
            class="link"
          >
            GitHub
          </a>

          <a
            href="https://vue-atividade07.vercel.app/"
            target="_blank"
            rel="noopener"
            class="link"
          >
            Vercel
          </a>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup>
import vueLogo from './assets/logo.svg'
</script>

<style scoped>
.page {
  min-height: 100vh;
  width: 100%;
  background-color: #1e1e1e;
  color: #ffffff;
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
}

/* HEADER */
.header {
  width: 100%;
  background-color: #2c2c2c;
}

.header-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 1rem 2rem;

  display: flex;
  align-items: center;
  gap: 1rem;
}

.logo {
  width: 50px;
}

h1 {
  font-size: 2rem;
  font-weight: bold;
}

.main {
  flex: 1;
  width: 100%;
}

.content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 3rem 2rem;
}

h2 {
  margin-bottom: 2rem;
  font-size: 2rem;
}

.links {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
}

.link {
  padding: 1rem 2rem;
  background-color: #42b883;
  color: white;
  text-decoration: none;
  border-radius: 10px;
  font-weight: bold;
  transition: 0.3s;
}

.link:hover {
  background-color: #2f8f68;
  transform: scale(1.05);
}
</style>