<template>
  <div class="getStarted">
    <div>
      <img class="spotify_logo" src="../assets/Spotify_Logo_.png" alt="spotify_logo">
    </div>
    <div>
      <h1 class="enjoy">Enjoy Listening To Music</h1>
    </div>
    <div>
      <h2>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sagittis enim purus sed phasellus. Cursus ornare id scelerisque aliquam.
      </h2>
    </div>
    <div>
      <button class="grosBoutonVert" @click="$router.push('/')" > Get Started </button>
    </div>

  </div>
</template>

<style>

.getStarted{
  width: 390px;
  height: 844px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.5),rgba(0,0,102,0.5)),url("../assets/ArianaGrande.jpg") ;
  background-size: cover;
  display: table-cell;
  vertical-align: top;
}
.spotify_logo{
  width: 250px;
  margin-top: 20px;
}

.enjoy{
  color: white;
  margin-top: 100%;
  text-align: center;
  font-size: 25px;
}
h2 {
  color: white;
  font-size: 15px;
  text-align: center;
  margin-right: 30px;
  margin-left: 30px;
}

.grosBoutonVert{
  width: 80%;
  height: 100px;
  color: white;
  font-size: 25px;
  background-color: rgb(66, 200, 60);
  border: none;
  border-radius: 15px;
  margin-top: 20px;
}
</style>
