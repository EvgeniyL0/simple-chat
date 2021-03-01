<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        simple-chat
      </h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
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
  const firebaseConfig = {
    apiKey: "AIzaSyAXqNNBoUzS8Q6uFgvG3JGTKtDC9EZSqTQ",
    authDomain: "simple-chat-11304.firebaseapp.com",
    projectId: "simple-chat-11304",
    storageBucket: "simple-chat-11304.appspot.com",
    messagingSenderId: "873881825834",
    appId: "1:873881825834:web:9e1453ce773786e96ec953"
  };
  // Initialize Firebase
  firebase.initializeApp(firebaseConfig);

export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
