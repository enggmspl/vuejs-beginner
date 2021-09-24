<template>
<div class="main">
  <div class="form">
      <h1>Say Hello!</h1>
      <input type="text" placeholder="Your Name">
      <input type="email" placeholder="Your Email">
      <select name="Services" id="">
        <option selected>1</option>
        <option>2</option>
      </select>
      <select name="Budget" id="">
        <option selected>10</option>
        <option>20</option>
      </select>
<textarea name="Message" placeholder="Your message here"></textarea>
<button class="btn">Submit</button>
</div>
</div>
</template>

<script>
export default {
  name: 'form'
}
</script>
<style scoped>

.main{
     background:linear-gradient(rgb(247, 34, 236),rgb(53, 170, 248)) ;
padding:5%;
}
 .form{

   background:white;
   width:300px;
   margin:auto;
   text-align: center;
   border-radius: 5px;
   height: auto;
   padding: 10px;
 }
 .form input,select,textarea{
   width: 250px;
   margin: auto;
   border:0;
   border-bottom: 1px solid gray;
   outline: none;
   margin-bottom: 30px;
 }
 .btn{
   width:80%;
   border-radius: 12px;
   background:linear-gradient(rgb(247, 34, 236),rgb(53, 170, 248)) ;
   border:0;
   color:white;
   margin:10px;
   padding-bottom: 5px;
      padding-top: 5px;


 }
 .btn:hover{

 }
 h1{
   font-size:20px;
   font-weight: 1000;
 }

</style>