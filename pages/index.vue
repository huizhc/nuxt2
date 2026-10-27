<template>
  <div class="container">
    <div>
      <h1 class="title">hello world</h1>
      <p class="subtitle">My Nuxt 2 application</p>
      <div class="links">
        <a
          href="https://v2.nuxt.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
    Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.title {
  font-size: 3rem;
  letter-spacing: 0.1rem;
  margin-bottom: 0.5rem;
}

.subtitle {
  font-size: 1.2rem;
  color: #526488;
  margin-bottom: 2rem;
}

.links {
  display: flex;
  gap: 1rem;
  justify-content: center;
}

.button--green,
.button--grey {
  display: inline-block;
  padding: 0.6rem 1.4rem;
  border-radius: 4px;
  text-decoration: none;
  font-size: 1rem;
  border: 1px solid #3b8070;
}

.button--green {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  color: #35495e;
  border-color: #35495e;
}
</style>
