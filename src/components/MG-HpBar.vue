<template>
  <section
    id="monster"
    class="container">
    <h2>Monster Health</h2>
    <div class="healthbar">
      <div class="healthbar__value"></div>
    </div>
  </section>
  <section
    id="player"
    class="container">
    <h2>Your Health</h2>
    <div class="healthbar">
      <div class="healthbar__value"></div>
    </div>
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

  #monster h2,
  #player h2 {
    margin: 0.25rem;
  }

  .healthbar {
    width: 100%;
    height: 40px;
    border: 1px solid #575757;
    margin: 1rem 0;
    background: #fde5e5;
  }

  .healthbar__value {
    background-color: #00a876;
    width: 100%;
    height: 100%;
  }
  
</style>