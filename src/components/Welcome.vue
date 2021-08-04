<template>
  <div class="app">
    <div class="container">
    <button type="button" class="pushable signUpBtn">
      <span class="front">
        <router-link to="/signUp">Sign Up</router-link>
      </span>
    </button>
    <button type="button" class="pushable signInBtn">
      <span class="front">
        Sign In
      </span>
    </button>
    <img alt="Vue logo" src="../assets/logo1000.png" width="500" height="400">
    <h1>Welcome to Quick Quiz</h1>
    <p>
      for playing quiz games with limited time
    </p>

  </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
.app {
  font-family: "Brush Script MT", cursive;
  text-align: center;
  color: wheat;
  background-color: #5E17EB;
  height: 100vh;
}

.signUpBtn{
  position: absolute;
  top: 20px;
  right: 140px;
}

.signInBtn{
  position: absolute;
  top: 20px;
  right: 20px;
}
.pushable {
    background: hsl(340deg 100% 32%);
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
    outline-offset: 4px;
    background-color: #DC7C41;
}
.front {
    display: block;
    padding: 8px 20px;
    border-radius: 12px;
    font-size: 1.25rem;
    background: hsl(345deg 100% 47%);
    color: white;
    transform: translateY(-6px);
    background-color: #FF914D;
}

  .pushable:active .front {
    transform: translateY(-2px);
  }

</style>
