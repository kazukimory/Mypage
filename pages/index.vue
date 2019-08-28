<template>
  <div class="container">
    <div class="term-head">
      <!-- <button class="red" onClick="if (/Chrome/i.test(navigator.userAgent)) { window.close(); } else { window.open('about:blank', '_self').close(); }"></button> -->
      <button class="red"></button>
      <button class="yellow"></button>
      <button class="green"></button>
      <span class="mrg-aboutme">ABOUT ME</span>
　　 </div>

    <div class="term-body">
    <p><span class="mrg">$</span><span class="mrg">name</span></p>
    <p><span class="white">Kazuki Mori</span></p>
    <p><span class="mrg">$</span><span class="mrg">age</span></p>
    <p><span class="white">21,     1998/05/19</span></p>
    <p><span class="mrg">$</span><span class="mrg">university</span></p>
    <p><span class="white">The University of Aizu (Third year University student)</span></p>
    <p><span class="mrg">$</span><span class="mrg">major</span></p>
    <p><span class="white">Computer science</span></p>
    <p><span class="mrg">$</span><span class="mrg">lab</span></p>
    <p><span class="white">Biomedical Information Technology</span></p>
    <p><span class="mrg">$</span><span class="mrg">skills</span></p>
    <p><span class="white">HTML / css / JavaScript</span></p>
    <p><span class="mrg">$</span><span class="mrg">hobby</span></p>
    <p><span class="white">Football  /  Watching movie  /  Listening to music</span></p>
    <p><span class="mrg">$</span><span class="mrg">account</span></p>
    <p><span class="white">click each other</span></p>
    <p><span class="mrg"><a href="https://github.com/s1250040" target="_blank">Github</a></span><span class="mrg">/</span>
    <span class="mrg"><a href="https://www.instagram.com/kazukimory/" target="_blank">Instagram</a></span><span class="mrg">/</span>
    <span class="mrg"><a href="https://twitter.com/kazukimory" target="_blank">Twitter</a></span><span class="mrg">/</span>
    <span class="mrg"><a href="https://www.facebook.com/K.M.KazukiMory" target="_blank">Facebook</a></span><span class="mrg">/</span>
    </p>
     <!-- <p><span class="mrg">Contact</span><span class="mrg"></span><router-link to="/form">To the page to send the form</router-link></p> -->
     <p><span class="mrg">$</span><span class="mrg">e-mail</span></p>
     <p><a href="mailto:s1250040a@gmail.com">From here</a></p>
     <br>
     <p><router-link to="/information">If you want to see GUI version</router-link></p>
　　 </div>
  </div>
</template>

<script>

export default {
}
</script>

<style scoped>
*:focus {
  outline: none;
}

.container{
  padding: 100px;
}

.term-head{
    padding: 0.5em 0.5em;
    color: #5d627b;
    background: rgb(227, 227, 228);
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    box-shadow: 0 3px 5px rgba(0, 0, 0, 0.22);
}

button{
    width: 20px;
    height: 20px;
    border-radius: 50%; 
}

.red{
  outline: 0;
  background: red;
}

.yellow{
  background: yellow;
}

.green{
  background:rgb(95, 207, 95);
}

.term-body{
    font-family: 'Verdana';
    padding: 0.5em 1em;
    /* color:rgb(7, 252, 117); */
    color: #fff;
    background: black;
    border-bottom-right-radius: 10px;
    border-bottom-left-radius: 10px;
    box-shadow: 0 3px 5px rgba(0, 0, 0, 0.22);
}
.term-body p {
    margin: 0; 
    padding: 0;
}

.mrg{
  margin-right : 20px;
}

.mrg-aboutme{
  margin-left : 35%;
}

a{
  color: rgb(8, 121, 4);
}

.white{
  /* color: #fff; */
  color:rgb(7, 252, 117);
}
</style>
