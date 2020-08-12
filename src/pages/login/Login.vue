<template>
    <div>
        <login-header></login-header>
        <login-dl></login-dl>
    </div>
</template>

<script>
import LoginHeader from './components/header'
import LoginDl from './components/dl'
export default {
  name: 'Login',
  components: {
    LoginHeader,
    LoginDl
  }
}
</script>

<style scoped>

</style>
