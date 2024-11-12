<script setup lang="ts">
</script>

<template>
  <div id="background">
    <div class="Top">
      <div>
        <div class="search">
          <input type="search"></input>
          <button @click="executeScript()"></button>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
#background {
  display: flex;
  flex-direction: row;
  height: 100vh;
  width: 100%;
}

input[type="search"] {
  border-radius: 5px;
  margin: 0 auto;
  display: block;
  margin-top: 10px;
  box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
}

input[type="search"]:hover {
  background-color: lightgray;
}

.Top {
  justify-content: center;
  align-items: center;
  width: 100%;
}
</style>

<script>
import axios from 'axios';
export default {
  methods: {
    executeScript() {
      axios.post()
    }
  }
}
</script>
