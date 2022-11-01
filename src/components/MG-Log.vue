<template>
  <section
    id="log"
    class="container">
    <h2>Battle Log</h2>
    <ul></ul>
  </section>
</template>

<style lang="scss" scoped>
  .container {
    text-align: center;
    padding: 0.5rem;
    margin: 1rem auto;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.26);
    border-radius: 12px;
  }
  
  #log ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  #log li {
    margin: 0.5rem 0;
  }

  .log--player {
    color: #7700ff;
  }

  .log--monster {
    color: #da8d00;
  }

  .log--damage {
    color: red;
  }

  .log--heal {
    color: green;
  }
</style>