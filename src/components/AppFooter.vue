<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
  <footer>

    <div class="footer-top d-flex justify-content-center">

      <img src="../pubblic/img/HelloIMG1669149314987.png" alt="Avada Charity">

    </div>

    <div class="footer-bottom">

      <div class="list-info">
        <ul class="d-flex justify-content-center">
          <li class="list-group-item">© 2012 - 2024</li>
          <li class="ms-4">
            
            <a href="#">Avada</a> 

            <span> is a </span> 

            <a href="#">Website Builder</a> 

            <span> for </span>

            <a href="#">WordPress</a>

            <span> and </span> 

            <a href="#">eCommerce</a>

           </li>

          <li class="ms-4">

            All Rights Reserved

          </li>

          <li class="ms-4">

            <span>Developed by </span>

            <a href="#">ThemeFusion</a>
             
          </li>
        </ul>
      </div>
      <div class="social-icon pt-4">
        <ul class="d-flex justify-content-center">
          <li class="list-group-item">
            <a href="#">
              <i class="fa-brands fa-square-facebook fa-2xl"></i>
          </a>
          </li>
          <li class="list-group-item ps-4">
            <a href="#">
              <i class="fa-brands fa-instagram fa-2xl"></i>
          </a>
          </li>
          <li class="list-group-item ps-4">
            <a href="#">
              <i class="fa-brands fa-x-twitter fa-2xl"></i>
          </a>
          </li>
          <li class="list-group-item ps-4">
            <a href="#">
              <i class="fa-brands fa-youtube fa-2xl"></i>
          </a>
          </li>
        </ul>
      </div>

    </div>

  </footer>
</template>

<style lang="scss" scoped>

footer{

 width: 100%;

  .footer-top{
    width: 100%;
    background-color: white;
    padding: 50px 0;
  }

  .footer-bottom{

    width: 100%;
    padding: 50px 0;
    background-color: #F9F9F9;

    a{
      text-decoration: none;
      color: $my-yellow;
    }
    .list-info{

      width: 80%;
      margin: 0 auto;
    }

   
  }
}

</style>
