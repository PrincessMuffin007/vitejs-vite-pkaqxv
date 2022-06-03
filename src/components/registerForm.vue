<template>
<form @submit.prevent="submitForm">

<div class="regElements">
<h3>Register to start Studying Today!</h3>
<p></p>

<label> Name:  </label>
<input type="name" required v-model= "name"/>
<p></p>

<label> Surname:  </label>
<input type="surname" required v-model= "surname"/>
<p></p>

<label> Desired course:  </label>
<input type="Dcourse" required v-model= "Dcourse"/>
<p></p>
</div>

<div class="submit">
<button> Register </button>
</div>
</form>

</template>

<script>

</script>

<style>


</style>