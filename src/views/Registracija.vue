<template>
<div>
  <div class="row">
    <div class="col">
      <h1 class="text-center mb-5">Registracija</h1>
    </div>
  </div>
  <div class="row">
    <div class="col"></div>
    <div class="col">
      <form @submit.prevent="signup">
        <div class="form-group">
          <label for="emailField">Email adresa</label>
          <input v-model="email" type="email" class="form-control" id="emailField" aria-describedby="emailHelp" placeholder="E-mail adresa">
          <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
        </div>
        <div class="form-group">
          <label for="passwordField">Lozinka</label>
          <input v-model="password" type="password" class="form-control" id="passwordField" placeholder="Lozinka">
        </div>
        <div class="form-group">
          <label for="confirm password">Potvrdi lozinku</label>
          <input v-model="confirm_pasword" type="confirm_pasword" class="form-control" id="confirm_paswordField"  placeholder="Potvrdi lozinku">
        </div>
        <button type="submit" class="btn btn-primary mt-5">Potvrdi</button>
      </form>
    </div>
    <div class="col"></div>
  </div>
</div>
</template>

<style >
.text-center {
     font-family: 'Playfair Display', serif;
     font-size:4em;
     margin-top: 20px; }
</style>

<script>
export default {
  data () {
    return {
      email: '',
      password: '',
      confirm_pasword: '',
    }
  },
  methods: {
    signup () {
      firebase.auth().signInWithEmailAndPassword(this.email, this.password).catch(function(error) {
        console.log(error);
      });
    }
  }
}
</script>