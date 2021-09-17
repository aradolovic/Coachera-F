<template>
<div class="box" id="bg">
  <div >
   
  <h1>Welcome to Coachera</h1>
    <h3>
      Sign In
    </h3>
    
    <div class="container">
      <div class="row">
        <div class="col-sm"></div>
          <div class="col-sm">
            <div class="white">
            <form>
              <div class="form-group">
              <label>Username</label>
              <input type="string" class="form-control"
              id="username" placeholder="Username" />
              </div>
              <div class="form-group">
              <label for="exampleInputEmail1">Email address</label>
              <input type="email" class="form-control"
              id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email" />
              <small id="emailHelp" class="form-text text-muted" ></small>
              </div>
              <div class="form-group">
              <label for="exampleInputPassword1">Password</label>
              <input type="password" class="form-control"
              id="exampleInputPassword1" placeholder="Password" />
              </div>
              <div class="form-group">
              <label for="exampleInputPassword1" font-style="bold">Confirm Password</label>
              <input type="password" class="form-control"
              id="exampleInputPassword1" placeholder="Confirm Password" />
              </div>
              <h1>


              </h1>
              <router-link to="/login" style=" color:white" >You alredy have an account? Log in</router-link>
              <h1>


              </h1>
            <button type="submit" class="btn btn-primary">Submit</button>
            </form>
          </div>
          </div>
        <div class="col-sm"></div>
      </div>
    </div>
  </div>
</div>

</template>

<style>
  #bg {
  background: url("../assets/sign.jpg") no-repeat center center fixed;
  -webkit-background-size : cover;
  -moz-background-size: cover;
  background-size: cover;
  -o-background-size: cover;
 
}
  .box {
  position:absolute;
  top:0px;
  right:0px;
  bottom:0px;
  left:0px;
}
.white {
 
}
</style>