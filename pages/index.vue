<template>
  <div class="root">
    <div class="container">
      <h1>Login</h1>
      <form action="">
        <input class='field1' type="text" placeholder="Username">
        <input class="field2" type="password" placeholder="password">
        <button class="submit">Submit</button>
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
}

::selection{
  background: #6649b8;
} 

.field1, .field2 {
  position: absolute;
}

.submit {
  background: -webkit-linear-gradient(right, #7101d1, #800fdc, #8e1ae8, #9d23f3, #ac2cff);
  border-radius: 5px;
  border: none;
}

</style>