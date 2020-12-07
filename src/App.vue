<template>
  <div id="app">
   <form-helper>
     <h2 class="title" slot="title1">Welcome to Form One!(Registration Form)</h2>
     <h2 class="title" slot="title2">Welcome to Form Two!(Login Form)</h2>
     <h2 class="title" slot="title3">Welcome to Form Three!(Application form)</h2>
     <form slot="form1">
  <div class="form-group">
    <label for="exampleFormControlInput1">First Name</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="First Name">
  </div>
    <div class="form-group">
    <label for="exampleFormControlInput1">Last Name</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Last Name">
  </div>
    <div class="form-group">
    <label for="exampleFormControlInput1">Email address</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
  </div>
    <div class="form-group">
    <label for="exampleFormControlInput1">Password</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="********">
  </div>
</form>
<form slot="form2">
  <div class="form-group">
    <label for="exampleFormControlInput1">Email address</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
  </div>
    <div class="form-group">
    <label for="exampleFormControlInput1">Password</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="**********">
  </div>
</form>
<form slot="form3">
  <div class="form-group">
    <label for="exampleFormControlInput1">First Name</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="First Name">
  </div>
    <div class="form-group">
    <label for="exampleFormControlInput1">Last Name</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="Last Name">
  </div>
    <div class="form-group">
    <label for="exampleFormControlInput1">Email address</label>
    <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
  </div>
  <div class="form-group">
    <label for="exampleFormControlSelect1">Please select position you are applying for</label>
    <select class="form-control" id="exampleFormControlSelect1">
      <option>Front End Engineer</option>
      <option>Back End Engineer</option>
      <option>Full Stack Developer</option>
      <option>UI/UX Designer</option>
      <option>Developer Advocate</option>
    </select>
  </div>
  <div class="form-group">
    <label for="exampleFormControlTextarea1">Please Tell Us More About You</label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
  </div>
</form>
    <button slot="button1" type="button" class="btn btn-primary">Register</button>
    <button slot="button2" type="button" class="btn btn-secondary">Login</button>
    <button slot="button3" type="button" class="btn btn-success">Apply</button>
  </form-helper>
  </div>
</template>
<script>
import formHelper from './components/Forms.vue'
export default {
  name: 'App',
  components: {
    'form-helper':formHelper,
  }
    }
</script>

<style scoped>
#app{
  width:86%;
  margin:auto;
}
.title{
  text-align: center;
}
.btn{
  width: 40%;
  margin-left: 30%;
  margin-right: 30%;
  margin-bottom: 100px;
  margin-top: 50px;
}
</style>