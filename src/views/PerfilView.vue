<script></script>

<template>
  <main>
    <div class="ti"><h1>login</h1></div>
    <div class="login">
      <form class="px-4 py-3">
        <div class="mb-3">
          <label for="exampleDropdownFormEmail1" class="form-label"
            >Email address</label
          >
          <input
            type="email"
            class="form-control"
            id="exampleDropdownFormEmail1"
            placeholder="email@example.com"
          />
        </div>
        <div class="mb-3">
          <label for="exampleDropdownFormPassword1" class="form-label"
            >Password</label
          >
          <input
            type="password"
            class="form-control"
            id="exampleDropdownFormPassword1"
            placeholder="Password"
          />
        </div>
        <div class="mb-3">
          <div class="form-check">
            <input
              type="checkbox"
              class="form-check-input"
              id="dropdownCheck"
            />
            <label class="form-check-label" for="dropdownCheck">
              Remember me
            </label>
          </div>
        </div>
        <button type="submit" class="btn btn-primary">Sign in</button>
      </form>
    </div>
  </main>
</template>
<style>
.px-4 {
  width: 350px;
  height: 150px;
  padding-left: 200px;
  
}
.login{ 
  width: 351px;
  height: 288px;
  top:301px;
  left: 454px;
  padding-left: 500px;
  padding-top: 0px;
  }
  .ti{
    padding-left: 620px;
    padding-top: 35px; }
 
</style>
