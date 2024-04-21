<script setup>
let id = 1;
</script>

<template>
  <main class="container-card">
    <div class="content-card">
      <div class="container-image">
        <img
          class="card-image"
          src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/1.svg"
          alt="imagem do pokemon"
        />
      </div>
      <div class="card-description">
        <div class="card-information">
          <h2 class="card-name">Bulbasaur</h2>
          <h2 class="card-id">{{ "N°" + id }}</h2>
        </div>
        <div class="card-details">
         <div class="pokemon-type">
            <p>
            Tipo
            </p>
            <span> 
                poison
            </span>
            <span> 
                poison
            </span>
        </div>
          <button>Ver mais</button>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.container-card {
  display: flex;
  height: 40vh;
  width: 15vw;
  background-color: #fff;
  border-radius: 10px;
  padding: 1rem;
  flex-direction: column;
}
.content-card {
  display: flex;
  flex-direction: column;
  /* gap: 1rem; */
  height: 40vh;
  width: 15vw;
  align-items: center;
  background-color: antiquewhite;
  border-radius: 10px;
}

.container-image {
  display: flex;
  justify-content: center;
  background-color: aquamarine;
  width: 100%;
  height: 50%;
  align-items: center;
}
.card-image {
  height: 15vh;
}
.card-description {
  display: flex;
  width: 100%;
  height: 50%;
  flex-direction: column;
}

.card-information {
  display: flex;
  background-color: blueviolet;
  width: 100%;
  height: 20%;
  align-items: center;
  justify-content: space-around;
  > h2 {
    font-size: 1.2rem;
  }
}

.card-details {
  display: flex;
  background-color: chocolate;
  height: 100%;
  justify-content: space-around;
  flex-direction: column;
  align-items: center;
  > p {
    align-self: start;
  }
  > button {
    width: 50%;
    border-radius: 5px;
    &:hover {
      cursor: pointer;
    }
  }
}

.pokemon-type{
    display: flex;
    width: 100%;
    height: 40%;
    background-color: aqua;
    justify-content: space-evenly;  
    align-items: center;
    > p {
        
    }
    > span {
        display: flex;
        width: 30%;
        align-items: center;
        justify-content: center;
        text-align: center;
        background-color: bisque;
        border-radius: 5px;
        padding: 0.2rem;
    }  
}
</style>
