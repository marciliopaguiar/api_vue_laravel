<template>

  <login-template>

      <span slot="menues">
         <img src="https://static.quizur.com/i/b/5b035c77702c13.471891555b035c775c3ff9.54480388.png" class="responsive-img">
      </span>
    
    <span slot="principal">

        <h2>Login</h2>

        <input input="text" placeholder="E-mail" value="">
        <input type="text" placeholder="Senha" value="">
        <button class="btn">Entrar</button>
        <router-link class="btn orange" to="/cadastro">Cadastra-se</router-link>
        </span>

    </span>
  

  </login-template>
 


</template>

<script>
import LoginTemplate from '@/templates/LoginTemplate'

export default {
  name: 'Login',
  data () {
    return {
    }
  },
  components: {
    LoginTemplate
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    
</style>
 