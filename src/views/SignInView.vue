<template>
  <div class="SignIn">
    <div>
      <img class="spotify_logo" src="../assets/Spotify_Logo_.png" alt="spotify_logo">
    </div>
    <div>
      <p class="signIn"> Sign In</p>
      <p class="potitTexte">If You Need Any Support <span class="vert">Click Here</span></p>
    </div>
    <div class="textArea">
      <TextAreaComponent message="Enteer Username Or Email"></TextAreaComponent>
      <TextAreaComponent message="Password"></TextAreaComponent>
      <p> Recovery Password</p>
      <BoutonVertComponenet message="Sign In" route="/"/>
      <img class="or" src="../assets/or.png"/>
      <img class="google" src="../assets/google.png"/>
      <img class="apple" src="../assets/apople.png"/>
      <p>Not a Member ? <span class="bleu">Register Now</span></p>
    </div>
  </div>
</template>

<style scoped>
.bleu{
  color: rgb(38, 126, 207);
}
.google{
  width: 10%;
  margin-right: 20% ;
}
.apple{
  width: 10%;
}
.or{
  width: 100%;
  height: 100%;
}
.signIn{
  margin-top: 40%;
  color: white;
  font-size: 40px;
}
.potitTexte{
  color: white;
}

.vert{
  color: green;
}
.SignIn{
  width: 390px;
  height: 844px;
  background-color: rgb(29, 28, 28) ;
  background-size: cover;
  display: table-cell;
  vertical-align: top;
}
.spotify_logo{
  width: 100px;
  margin-top: 10px;
}
</style>

<script>
import TextAreaComponent from "@/components/TextAreaComponent";
import BoutonVertComponenet from "@/components/BoutonVertComponenet";
export default {
  components: {BoutonVertComponenet, TextAreaComponent},
}

</script>