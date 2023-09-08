<template>
  <div id="app">
    <h1>เกมเป่ายิ้งฉุบ</h1>
    <GameComponent />
  </div>
</template>

<script>
import GameComponent from './components/game1.vue'

export default {
  components: {
    GameComponent,
  },
};
</script>

<style>
#app {
  text-align: center;
  color: #d2d900;
  font-size: 30px;
  text-shadow: 5px 3px 5px rgb(232, 123, 0);
  margin-top: 0px;
  width: 70%; 
  height: 110vh; 
  display: flex;
  flex-direction: column;
}

h1 {
  font-size: 3.5em;
}
h3{
  margin:20px;
}
.round-button{
  margin:50px;
}
.player1-name {
  color: #00d9ff; 
  text-shadow: 3px 5px 3px rgb(0, 11, 212);
  font-size: 40px;
}

.player2-name {
  color: #00d9ff; 
  text-shadow: 3px 5px 3px rgb(46, 0, 197);
  font-size: 40px;
}


.player-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}

.reset-button {
  margin-left: 70px; 
  background-color: #17c407; 
  color: #ffffff; 
  font-size: 25px;
  border-radius: 30px;
  border: 5px solid #ffffff;  
}

.reset-button:hover {
  background-color: #024b0b; 
}
.round-button:hover {
  background-color: #8a0808ee; 
}

.round-button {
  
  background-color: #fe0b0b; 
  color: #fff;
  font-size: 25px;
  border-radius: 30px;
  border: 5px solid #ffffff;  
}

.score-container {
  background-color: #eb86ae; 
  color: #fafafa; 
  font-size: 30px;
  padding: 3px; 
  margin-top: 15px; 
  text-align: center; 
  border-radius: 30px; 
  border: 2px solid #ff0a4b; 
  border-width: 10px;
  max-width: 400px; 
  margin: 20px auto;
}
.score-text {
  margin: 0; 
}
</style>


