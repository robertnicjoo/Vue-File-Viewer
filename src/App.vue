<template>
  <div id="app">
    <a target="_blank" href="https://irando.co.id">
      <img alt="Irando logo" src="../assets/logo_dark.png" />
    </a>
    <div class="fileViewer">
      <file-viewer
        filename="Indonesia_Raya.docx"
        url="https://filebin.net/9iujdtq316oi5o5o/Indonesia_Raya.docx?t=az80srol"
      />
    </div>
  </div>
</template>

<script>
import "file-viewer";

export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.fileViewer {
  margin: 5rem;
  border: 1px solid gray;
  border-radius: 0.25rem;
}
</style>
