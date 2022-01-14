<template>
  <div container>
    <img avatar src="./assets/kid.png" />
    <p title>@webbendr</p>
    <div button twitch >Twitch</div>
    <div button youtube >Youtube</div>
    <div button spotify >Spotify</div>
    <div button instagram >Instagram</div>
  </div>
</template>

<script>
  export default {
    name: 'App',
  }
</script>

<style lang="scss">
  body {
    background: #20125d;
    color: #fff;
    font-family: 'Courier New';
    font-size: 20px;
    margin: 0;
    text-align: center;
  }
  [container] {
    box-sizing: border-box;
    min-height: 100vh;
    padding: 40px 20px;
  }
  [avatar] {
    width: 6rem;
    height: 6rem;
    border: 4px solid #4900c2;
    border-radius: 50%;
  }
  [title] {
    font-weight: bold;
    margin: 10px auto 40px;
    font-size: 30px;
  }
  [button] {
    width: 100%;
    border: 3px solid;
    border-radius: 50px;
    transform: rotate(-15deg);
    padding: 15px 0;
    margin-bottom: 20px;
  }
  [twitch] {
    border-color: #863dff;
  }
  [youtube] {
    border-color: #df125d;
  }
  [spotify] {
    border-color: #00f600;
  }
  [instagram] {
    border-color: #fc00ff;
  }
</style>
