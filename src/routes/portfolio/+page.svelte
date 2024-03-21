<script>
  import myphoto1 from "$lib/images/myphoto1.jpeg";
  import myphoto2 from "$lib/images/myphoto2.jpeg";
  import myphoto3 from "$lib/images/myphoto3.jpeg";
  import myphoto4 from "$lib/images/myphoto4.jpeg";
  import myphoto5 from "$lib/images/myphoto5.jpeg";
  import myphoto6 from "$lib/images/myphoto6.jpeg";
</script>

<div class="container">
  <img alt="Моя кошка 1" src={myphoto1} width="400" />
  <br />
  <img alt="Моя кошка 2" src={myphoto2} width="400" />
  <br />
  <img alt="Моя кошка 3" src={myphoto3} width="400" />
  <br />
  <img alt="Моя кошка 4" src={myphoto4} width="400" />
  <br />
  <img alt="Моя кошка 5" src={myphoto5} width="400" />
  <br />
  <img alt="Моя кошка 6" src={myphoto6} width="400" />
</div>

<style>
  .container {
    margin: 50px auto;
    max-width: 800px;
    padding: 0 20px;
  }
</style>
