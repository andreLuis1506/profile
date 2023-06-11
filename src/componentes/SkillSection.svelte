<script>
  import HexagonLine from "./HexagonLine.svelte"
  import Hexagon from "./Hexagon.svelte"
</script>

<div class="container">
  <div class="column">
    <h2>Habilidades</h2>
    <HexagonLine even>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
    <HexagonLine odd>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
  </div>
  <div class="column">
    <h2>Linguas</h2>
    <HexagonLine even>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
    <HexagonLine odd>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
    <HexagonLine even>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
  </div>
  <div class="column">
    <h2>Ferramentas</h2>
    <HexagonLine even>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
    <HexagonLine odd>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
    <HexagonLine even>
      <Hexagon />
      <Hexagon />
    </HexagonLine>
  </div>
</div>

<style>
  .container{
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
    width: 60%;
  }
  .column{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    flex-direction: column;
  }
</style>