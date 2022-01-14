<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <div container>
    <img avatar src="./assets/kid.png" />
    <p title>@webbendr</p>
    <div button twitch >
      <span>Twitch</span>
      <i class="fa fa-twitch"></i>
    </div>
    <div button youtube >
      <i class="fa fa-youtube"></i>
      <span>Youtube</span>
    </div>
    <div button spotify >
      <span>Spotify</span>
      <i class="fa fa-spotify"></i>
    </div>
    <div button instagram >
      <i class="fa fa-instagram"></i>
      <span>Instagram</span>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App',
  }
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
  }
  body {
    background: #20125d;
    color: #fff;
    font-family: 'Courier New';
    font-size: 20px;
    margin: 0;
    text-align: center;
  }
  [container] {
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
    display: flex;
    align-items: center;
    background-color: #13054f;
    padding: 15px;
    margin-bottom: 20px;
    span {
      margin-left: auto;
      margin-right: auto;
    }
    i {
      font-size: 26px;
    }
  }
  [twitch] {
    border-color: #863dff;
    i {
      color: #863dff;
    }
  }
  [youtube] {
    border-color: #df125d;
    i {
      color: #df125d;
    }
  }
  [spotify] {
    border-color: #00f600;
    i {
      color: #00f600;
    }
  }
  [instagram] {
    border-color: #fc00ff;
    i {
      color: #fc00ff;
    }
  }
</style>
