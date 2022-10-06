<template>
  <div class="container">
    <div class="container-form">
      <form>
        <label for="userName">User:</label><br>
        <input type="text" id="userName" name="userName">
        <br><label for="passUser">Password:</label><br>
        <input type="text" id="passUser" name="passUser"><br>
        <button type="submit" value="Submit">Submit</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppContent"
}
</script>

<style scoped>

@font-face {
  font-family: "FjallaOne-Regular";
  src: local("FjallaOne-Regular"),
  url(../fonts/FjallaOne-Regular.ttf) format("truetype");
}


.container{
  height: 500px;
  width: 500px;
  background-color: whitesmoke;
  position: absolute;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.container-form{
  position: absolute;
  left: 50%;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
  font-size: 30px;
  font-family: FjallaOne-Regular;
}

.container-form button{
  margin-top: 10px;
  border: none;
  border-radius: 20px;
  padding: 10px;
  background-color: dodgerblue;
}

.container-form button:hover{
  background-color: skyblue;
}


.container-form input{
  border-radius: 20px;
}

</style>