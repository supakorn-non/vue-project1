<template>
  <div class="bg">
    <div class="icon">
      <img src="../assets/logo250.png">
    </div>
    <body class="block">
      <div class="insideBlock">
        <div class="line">
          <p class="fsize">CREATE YOUR ACCOUNT</p>
          <div class="blockInput">
            <label class="label">
            <span class="span">email</span>
            <input name="email" type="text" class="input">
            </label>
          </div>
          <div class="blockInput">
            <label class="label">
            <span class="span">username</span>
            <input  name="username" type="text" class="input">
            </label>
          </div>
          <div class="blockInput">
            <label class="label">
            <span class="span">password</span>
            <input  name="password" type="password" class="input">
            </label>
          </div>
          <div class="blockInput">
            <label class="label">
            <span class="span">confirm password</span>
            <input  name="confirm" type="password" class="input">
            </label>
          </div>
          <div class="blockButton">
            <button class="pushableRe" type="submit">
              <span class="frontRe">SUBMIT</span>
            </button>
          </div>
        </div>
      </div>
    </body>
    <div class="blockAcc">
        <p class="haveAcc" >
          Already have an account?
          <a href="/signIn">Sign In</a>
        </p>
      </div>
  </div>
</template>


<script>
export default {

}
</script>

<style>
.icon{
    display: flex;
    justify-content: center;
}
.bg{
    background-image: url("../assets/bg.png");
    height: 100vh;
}
.block{
  margin-left: auto;
  margin-right: auto;
  margin-top: 0px;
  max-width: 450px;
  background-color: #5E17EB;
}
.insideBlock{
    background-color: white;
    border: 1px solid #FF914D;
    border-radius: 1px;
    margin: 0 0 10px;
    padding: 16px 0;
    border-radius: 6px;
}
.h1 {
  text-align: center;
  margin-bottom: 20px;
}
.line{
  margin: 0 40px 6px;
}
.fsize{
  font-family: "Brush Script MT", cursive;
  color: #5E17EB;
  text-align: center;
  font-size: 20px;
  margin-top: 10px;
}
.blockInput{
    align-items: center;
    background: white;
    border: 2px solid #FF914D;
    border-radius: 4px;
    display: block;
    font-size: 14px;
    margin-bottom: 20px;
    font-family: "Brush Script MT", cursive;
}
.label{
    display: flex;
    height: 36px;
    -webkit-box-flex: 1;
    flex: 1 0 0;
    padding: 0;
    position: relative;
    margin: 0;
    min-width: 0;
}
.span{
    color: rgba(var(--f52,142,142,142),1);
    font-size: 12px;
    height: 36px;
    left: 8px;
    line-height: 36px;
    overflow: hidden;
    pointer-events: none;
    position: absolute;
    right: 0;
    text-overflow: ellipsis;
}
.input{
    background: white;
    border: 0;
    margin: 0;
    outline: 0;
    overflow: hidden;
    padding: 9px 0 7px 8px;
    text-overflow: ellipsis;
}
.blockButton{
  flex: 0 0 auto;
  align-content: stretch;
  margin-left: 30px
}
.pushableRe {
    background: hsl(340deg 100% 32%);
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
    outline-offset: 4px;
    background-color: #DC7C41;
}
.frontRe {
    display: block;
    padding: 8px 20px;
    border-radius: 12px;
    font-size: 1.25rem;
    background: hsl(345deg 100% 47%);
    color: white ;
    transform: translateY(-6px);
    background-color: #FF914D;
    width: 40vh;
    font-family: "Brush Script MT", cursive;
    
}

.pushableRe:active .frontRe {
  transform: translateY(-2px);
}
.haveAcc{
    color: #5E17EB;
    font-size: 16px;
    margin: 15px;
    text-align: center;
    font-family: "Brush Script MT", cursive;
}
.blockAcc{
    background-color: white;
    border: 1px solid #FF914D;
    border-radius: 1px;
    margin: 20px 542px;
    padding: 10px 0;
    border-radius: 6px;
}
</style>