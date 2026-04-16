<template>
  <div class="page">
    <header class="header">
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/9/95/Vue.js_Logo_2.svg"
        alt="Vue logo"
        class="logo"
      />
      <h1>Projeto Vue</h1>
    </header>

    <main class="main">
      <h2>Links do Projeto</h2>

      <div class="links">
        <a
          href="https://github.com/Akainor/vue-atividade07"
          target="_blank"
          rel="noopener"
        >
          GitHub
        </a>

        <a
          href="https://vue-atividade07.vercel.app/"
          target="_blank"
          rel="noopener"
        >
          Vercel
        </a>
      </div>
    </main>
  </div>
</template>

<style>
/* RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* BASE */
body {
  font-family: Arial, sans-serif;
  background-color: #111;
  color: #fff;
}

/* PAGE */
.page {
  min-height: 100vh;
}

/* HEADER */
.header {
  width: 100%;
  background-color: #222;
  padding: 16px 24px;

  display: flex;
  align-items: center;
  gap: 12px;
}

.logo {
  width: 40px;
}

/* MAIN */
.main {
  padding: 24px;
}

/* TEXT */
h1 {
  font-size: 1.8rem;
}

h2 {
  margin-bottom: 16px;
}

/* LINKS */
.links {
  display: flex;
  gap: 12px;
}

.links a {
  background-color: #42b883;
  color: white;
  padding: 10px 16px;
  text-decoration: none;
  border-radius: 6px;
  transition: 0.2s;
}

.links a:hover {
  background-color: #2f8f68;
}
</style>