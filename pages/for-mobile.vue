<template>
<div class="container">
    <router-link to="/"><img src="~/assets/iTerm2-v3-Hero-logo-icon.jpg" alt="home" class="term"></router-link>
    <div class="letter">
        <p>About me</p>
        <P><span class="d">Kazuki Mori</span><span class="d">1998/5/19</span></P>
        <p>The University of Aizu (Third year student)</p>
        <p>Major : Computer science</p>
        <p>Lab : Biomedical Information Technology</p>
        <p>Skills : </p>
        <p>HTML / css / JavaScript / Flutter</p>
        <p>Hobby : </p>
        <p>Football  /  Watching movie  /  Listening to music</p>
        <p>Account : </p>
        <p><span class="d"><a href="https://github.com/s1250040" target="_blank">Github</a></span><span class="mrg">/</span>
        <span class="d"><a href="https://www.instagram.com/kazukimory/" target="_blank">Instagram</a></span><span class="mrg">/</span>
        <span class="d"><a href="https://twitter.com/kazukimory" target="_blank">Twitter</a></span><span class="mrg">/</span>
        <span class="d"><a href="https://www.facebook.com/K.M.KazukiMory" target="_blank">Facebook</a></span><span class="mrg">/</span>
        </p>
        <p>Letter me : <a href="mailto:s1250040a@gmail.com">From here</a></p>
        <p></p>

    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Special+Elite&display=swap');
@media screen and (min-width:300px) { 
  
body {
    padding-top:20px;
}

.term{
    width: 50px;
    height: 50px;
}

body {
  background: linear-gradient(#ccc, #fff);
  font: 14px sans-serif;
  padding: 20px;
}
p{ 
    font-family: 'Special Elite', cursive;
}
.letter {
  /* background: #fff; */
  
  background: #FFFDE7;
  box-shadow: 0 0 10px rgba(0,0,0,0.3);
  margin: 26px auto 0;
  max-width: 550px;
  min-height: 300px;
  padding: 24px;
  position: relative;
  width: 80%;
}
.letter:before, .letter:after {
  content: "";
  height: 98%;
  position: absolute;
  width: 100%;
  z-index: -1;
}
.letter:before {
  /* background: #fafafa; */
  background: #FFFDE7;
  box-shadow: 0 0 8px rgba(0,0,0,0.2);
  left: -5px;
  top: 4px;
  transform: rotate(-2.5deg);
}
.letter:after {
  /* background: #f6f6f6; */
  background: #FFFDE7;
  box-shadow: 0 0 3px rgba(0,0,0,0.2);
  right: -3px;
  top: 1px;
  transform: rotate(1.4deg);
}

.d {
    margin-right : 20px;
 }
}
</style>