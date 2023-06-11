<script lang="ts">
  export let even: boolean = false
  export let odd: boolean = false
</script>

<div class="line" class:even class:odd>
  <slot></slot>
</div>

<style>
  .line{
    display: flex;
    justify-content: center;
    align-items: start;
    width: 100%;
  }

  .even{
    margin-top: -23px;
    margin-left: 85px;
    display: flex;
    justify-content: start;
    width: 100%;
  }

  .odd{
    display: flex;
    justify-content: start;
    width: 100%;
    margin-top: -23px;
  }

</style>