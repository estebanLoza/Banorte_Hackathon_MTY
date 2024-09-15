<script>
  import NavBar from "./lib/NavBar.svelte";
  


  //Importación de imagenes Gastos
  import PieGrafica from './lib/img/PieGrafica.png';
</script>


<NavBar/>

<main>
    <div id="Gastos">
      <img src={PieGrafica} alt="Grafica pie para mostrar sobre la educacion financiera">
      <div id="CuentaDinero">
        <p>$1,543.52</p>
        <p>Total de Gastos</p>
        <p>1 Mayo --> Hoy</p>

      </div>
    </div>
</main>

<style>
  main{
    
    width: 100%;
    
  }



  
</style>
