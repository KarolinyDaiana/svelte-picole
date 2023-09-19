<script>
  let countSim = 0
  const mais = () => {
    countSim++;
  }

  let countNao = 0
  const menos = () => {
    countNao++;
  }

</script>

<button on:click={mais}>
  SIM -> {countSim}
</button>

<button on:click={menos}>
  NÃO -> {countNao}
</button>
