<template>
  <div class='home-view'>
    <h1 class='mb-4'>Spende Wärme</h1>
    <b-container
      class='mx-auto p-4 text-center home-card'
    >
    <br>
      <h2>Was machst du wenn dir kalt ist?
      </h2>
      <p>
        Ins Warme gehen oder dich dicker anziehen?
        Für viele Menschen ist das leider keine Option im Winter.
      </p>
      <br>
      <h2>Wir haben entschieden zu helfen!</h2>
      <p>Mit unserer Aktion wolllen wir auf das alljährliche Problem aufmerksam machen. <br>
        Gerade in Flüchltlingscamps in Syrien, Libanon oder dem Irak bedeutet Winter oft Angst und manchmal sogar Tod. Mit einer Spende an die UNO-Flüchtlingshilfe können wir das zusammen ändern.</p>

      <b-button href='#' variant='primary'>Jetzt Spenden</b-button>
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style>
  .home-card{
    background-color:lightblue;
    border-radius: 9px;
  }
</style>
