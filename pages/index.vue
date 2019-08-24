<template>
  <div class="container">
    <div class="term-head">
      <button class="red"></button>
      <button class="yellow"></button>
      <button class="green"></button>
      <span class="mrg-aboutme">ABOUT ME</span>
　　 </div>

    <div class="term-body">
    <p><span class="mrg">Name</span><span class="mrg">-----></span><span class="white">Kazuki Mori</span></p>
    <p><span class="mrg">Age</span><span class="mrg">-----></span><span class="white">21,     1998/05/19</span></p>
    <p><span class="mrg">University</span><span class="mrg">-----></span><span class="white">The University of Aizu  (Third year University student)</span></p>
    <p><span class="mrg">Major</span><span class="mrg">-----></span><span class="white">Computer science</span></p>
    <p><span class="mrg">Lab</span><span class="mrg">-----></span><span class="white">Biomedical Information Technology</span></p>
    <p><span class="mrg">Skills</span><span class="mrg">-----></span><span class="white">HTML / css / JavaScript</span></p>
    <p><span class="mrg">Hobby</span><span class="mrg">-----></span><span class="white">Football  /  Watching movie  /  Listening to music</span></p>
    <p><router-link to="/information">open more information</router-link></p>
    <br>
    <br>
    <p><span class="mrg">Github</span><span class="mrg">-----></span><a href="https://github.com/s1250040" target="_blank">click here</a></p>
    <p><span class="mrg">Instagram</span><span class="mrg">-----></span><a href="https://www.instagram.com/kazukimory/" target="_blank">click here</a></p>
    <p><span class="mrg">Twitter</span><span class="mrg">-----></span><a href="https://twitter.com/kazukimory" target="_blank">click here</a></p>
    <p><span class="mrg">FaceBook</span><span class="mrg">-----></span><a href="https://www.facebook.com/K.M.KazukiMory" target="_blank">click here</a></p>
    <br>
    <br>
     <p><span class="mrg">Contact</span><span class="mrg">-----></span><router-link to="/form">To the page to send the form</router-link></p>
      <!-- <form action="confirm.php" method="post">
        <p>
         <label for="yourname">お名前</label>
         <input type="text" name="yourname" placeholder="名前">
        </p>
        <p>
         <label for="comment">コメント</label>
         <textarea id="comment" name="comment" placeholder="ここには自由にコメントを記入してください"></textarea>
        </p>
        <p>
         <label for="mail">メール：</label>
         <input id="mail" type="email" name="mail">
       </p>
       <input type="submit" value="送信する">
      </form> -->
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
