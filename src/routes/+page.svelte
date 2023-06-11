<script lang="ts">
  import BaseButton from "../componentes/BaseButton.svelte";
  import ProfileImg from "../componentes/ProfileImg.svelte";
</script>


<section id="apresentation">
  <ProfileImg />
  <h1 class="title"> André Luis dos Santos</h1>
  <p class="subtitle">{'< Desenvolvedor />'}</p>
  <div class="button-group">
    <BaseButton>Github</BaseButton>
    <BaseButton>Linkedin</BaseButton>
    <BaseButton>Email</BaseButton>
  </div>
</section>

<style>
  :global(){
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@100;200;300;400;500;600&display=swap');
  }
  :global(body){
    background-color: #ECECEC;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  section{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 80vh;
    width: 1500px;
  }

  .button-group{
    display: flex;
    justify-content: space-between;
    width: 230px;
    margin-top: 25px;
  }

  .title{
    font-family: 'Roboto Mono', monospace;
    font-size: 3.125rem;
    line-height: 65px;
    font-weight: 200;
    border: none;
    margin: 0;
  }
  .subtitle{
    font-family: 'Roboto Mono', monospace;
    font-size: 2.5rem;
    line-height: 52px;
    font-weight: 100;
    margin: 0;
  }


</style>