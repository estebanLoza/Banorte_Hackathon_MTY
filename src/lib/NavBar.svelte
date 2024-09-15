<script>
  import logoBanorte from './img/logoBanorte.png';
  import iconoNotificacion from './img/iconoNotificacion.png';
</script>
  

<header>
  <nav>
    <img id="logoBanorte" src={logoBanorte} alt="Logo de Banco Banorte">
    <img id="Notificacion" src={iconoNotificacion} alt="Icono de notificación">
  </nav>
</header>


<style>
  header{
    background-color:#EB0029;
    width: 100vw;
    height:3.7rem;
  }

  nav{
    /* border:1px solid green; */
    width: auto;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding:0 6% 0 6%;
  }


  nav #logoBanorte{
    width: 12%;
  }

  nav #Notificacion{
    width: 6.5%;
  }



</style>