<template>
  <div class="chooseMode">
    <div>
      <img class="spotify_logo" src="../assets/Spotify_Logo_.png" alt="spotify_logo">
    </div>
    <div>
      <h1 class="choose">Choose Mode</h1>
    </div>
    <div>
      <img class="darkMode" src="../assets/darkmode-removebg-preview.png">
      <img class="lightMode" src="../assets/light-mode.png">
    </div>

    <div>
      <k1 class="darkModeText">Dark Mode</k1>
      <k1 class="lightModeText"> Light Mode</k1>
    </div>
    <div>
      <BoutonVertComponenet message="Continue" route='/'> Continue </BoutonVertComponenet>
    </div>

  </div>
</template>

<style>

.darkModeText{
  margin-right: 20%;
  color: white;
}
.lightModeText{
  color: white;
}
.darkMode{
  width: 20%;
  margin-right: 20%;
}
.lightMode{
  width: 20%;
}
.chooseMode{
  width: 390px;
  height: 844px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.5),rgba(0,0,102,0.5)),url("../assets/lameufla.png") ;
  background-size: cover;
  display: table-cell;
  vertical-align: top;
}

.choose{
  color: white;
  margin-top: 100%;
  text-align: center;
  font-size: 25px;
}
.spotify_logo{
  width: 250px;
  margin-top: 20px;
}
</style>

<script>
import BoutonVertComponenet from "@/components/BoutonVertComponenet";
export default {
  components: {BoutonVertComponenet},
  data: function(){
  },
  methods: {
    toggleClass: function(){

      this.isActive = !this.isActive;

    }
  }
}

</script>