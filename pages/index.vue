<template>
  <div class="root">
    <div class="container">
      <h1>Login</h1>
      <form action="" class="form-inner">
        <input class='field1' type="text" placeholder=" Username">
        <input class="field2" type="password" placeholder=" Password">
        <button class="submit">Login</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  layout: "defaultStyles"
}
</script>

<style>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  justify-content: center;
  background: var(--bg-primary);
  height: 100%;
  max-width: 450px;
  padding: 40px 50px 65px 50px;
  border-radius: 40px;
  margin-top: 200px;
  box-shadow: 0px 15px 20px rgba(0,0,0,0.1);
}

.field1, .field2 {
  border: 1px solid lightgray; 
  outline: none;
  background: #34343d;
  border-radius: 5px;
  margin: 25px;
  margin-bottom: 1px;
  width: 65%;
  transition: all 0.3s ease;
}

.field1:focus, .field2:focus {
  border-color: #6649b8;
}

.field1, .field2 ::placeholder {
  color: #999;
}

.submit {
  background: -webkit-linear-gradient(right, #7101d1, #800fdc, #8e1ae8, #9d23f3, #ac2cff);
  border-radius: 5px;
  border: none;
  cursor: pointer;
  width: 65%;
  margin: 25px;
}

</style>