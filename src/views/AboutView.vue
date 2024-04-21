<script setup>

let name = "Anderson ";
</script>

<template>
  <main>
    <div class="main">
      <h2>Lembrete</h2>
      <div class="sub">
        <p>A sorte do dia é ser herdeiro</p>
      </div>
    </div>
    <div class="about">
      <p>Dito isso...</p>
      <h1>{{ name }}, vai estudar seu vagabundo!</h1>
      <span>
        <h3>ass: seu pai</h3>
      </span>
    </div>
  </main>
</template>

<style scoped>
main {
  background-color: aliceblue;
  height: 50vh;
  color: black;
  border-radius: 35px;
  display: flex;
}

.about {
  border-radius: 35px;
  background-color: bisque;
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;
  flex-direction: column;
}

h1 {
  font-size: 2rem;
  font-weight: 700;
}

span {
  display: flex;
  align-items: end;
  text-align: right;
  justify-content: right;
  /* background-color: aqua; */
  width: 100%;
  height: 20%;
  padding-right: 25px;
  h3 {
    font-weight: 500;
  }
}

.main {
  h2 {
    top:200px;
    position: absolute;
    font-size: 2rem;
    font-weight: 700;
  }
  > p {
    font-weight: 700;
    font-size: 1.3rem;
  }
  display: flex;
  align-items: center;
  flex-direction: column;
  /* background-color: aqua; */
  width: 100%;
  height: 100%;

}

.sub{
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  /* background-color: aqua; */
  width: 100%;
  height: 100%;
}
</style>
