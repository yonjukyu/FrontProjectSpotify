<template>
  <div class="registerOrSignUp">
    <div>
      <img class="spotify_logo" src="../assets/Spotify_Logo_.png" alt="spotify_logo">
    </div>
    <div class="BoutonAndSign">
      <p class="enjoyAgain">Enjoy Listening To Music</p>
      <button class="BoutonVert" @click="$router.push('/')" > Register </button>
      <k1 class="signIn"> Sign in</k1>
    </div>
    
    <img class="Billie" src="../assets/billiecoté.png">
  </div>
</template>

<style>
.enjoyAgain{
  color: white;
  font-size: 30px;
}
.signIn{
  color: white;
  font-size: 40px;
}
.BoutonAndSign{
  margin-top: 50%;
}
.BoutonVert{
  width: 40%;
  height: 70px;
  color: white;
  font-size: 25px;
  background-color: rgb(66, 200, 60);
  border: none;
  border-radius: 15px;
  margin-top: 20px;
  margin-right: 20%;
}
.registerOrSignUp{
  width: 390px;
  height: 844px;
  background-image: linear-gradient(to bottom, rgb(0,0,0),rgb(40,40,40)) ;
  background-size: cover;
  display: table-cell;
  vertical-align: top;
}
.spotify_logo{
  width: 400px;
  margin-top: 100px;
}
.Billie{
  width: 60%;
  margin-left: -40% ;
}
</style>

<script>
export default {
  components: {},
  data: function(){
  },
  methods: {
    toggleClass: function(){

      this.isActive = !this.isActive;

    }
  }
}

</script>