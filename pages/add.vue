<template>
  <div class="container">
    <div class="forms">
      <form action="#">
        <div class="input-field">
          <input type="text" placeholder="First Name" required />
        </div>
        <div class="input-field">
          <input type="text" placeholder="Middle Name" required />
        </div>
        <div class="input-field">
          <input type="text" placeholder="Last Name" required />
        </div>
        <div class="input-field">
          <input type="text" placeholder="Age" required />
        </div>
        <div class="checkbox-text">
          <input type="radio" id="maleGender" name="gender" required />
          <label for="maleGender" class="text">Male</label>
          <input type="radio" id="femaleGender" name="gender" required />
          <label for="femaleGender" class="text">Femlae</label>
        </div>
      </form>
    </div>
    <div class="button">
      <input type="button" value="SAVE" id="save" />
      <input type="button" value="CANCEL" id="cancel" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'add',
}
</script>

<style lang="scss" scoped>
body {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #4070f4;
}

.container {
  max-width: 430px;
  width: 100%;
  background: rgb(255, 255, 255);
  border-radius: 10px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.5);
  overflow: hidden;
  top: 30%;
  left: 30%;
  // margin-top: -50px;
  // margin-left: -50px;
  position: absolute;
}

.container .forms {
  display: flex;
  align-items: center;
  height: 100%;
  width: 50%;
  transition: height 0.2s ease;
  //   background: red;
}

.container .form {
  width: 50%;
  padding: 30px;
  background: #fff;
}

.form .input-field {
  position: relative;
  height: 50px;
  width: 100%;
  margin-top: 30px;
}

.input-field input {
  position: relative;
  height: 100%;
  width: 100%;
  border: none;
  outline: none;
  font-size: 16px;
  border-bottom: 2px solid #ccc;
  border-top: 2px solid transparent;
  transition: all 0.2s ease;
}

.form .checkbox-text {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 20px;
}

.checkbox-text .checkbox-content {
  display: flex;
  align-items: center;
}

.checkbox-content input {
  margin: 0 8px -2px 4px;
  accent-color: #05102c;
}
.form .button {
  margin-top: 35px;
}

.button {
  border-top: 3px solid #ccc;
  padding: 3px;
}
.button input {
  border: 1px solid  rgb(63, 86, 107);
  border-radius: 3px;
  padding: 3px;
  width: 100px;
}

.button input:hover {
  background-color: rgb(1, 45, 83);
  color: white;
}

 #cancel:hover {
  background-color: red;
  color: white;
}
</style>
