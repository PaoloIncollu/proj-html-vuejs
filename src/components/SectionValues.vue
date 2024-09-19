<script>
export default {
  data() {
    return { 
      
    }
  }
}
</script>

<template>
  <section>
    <div class="values-container text-white">

        <div class="text-center">
            <h2 class="text-uppercase">
                Our Values
            </h2> 
            
            <div class="line my-4">

            </div> 

            
            <span>
                Think Big. Act Bigger
            </span>
            
        </div>

        <div class="my-row row">
            <div class="my-card card text-center col-sm-6 col-md-4 col-lg-3">
                <i class="fa-solid fa-droplet"></i>
                <div class="card-body text-white">
                    <h5 class="card-title">Clean Water</h5>
                    <p class="card-text">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <a href="#" class="btn my-btn text uppercase">Learn more</a>
                </div>
            </div>
            <div class="my-card card text-center col-sm-6 col-md-4 col-lg-3">
                <i class="fa-solid fa-stethoscope"></i>
                <div class="card-body text-white">
                    <h5 class="card-title">Vaccination</h5>
                    <p class="card-text">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <a href="#" class="btn my-btn text uppercase">Learn more</a>
                </div>
            </div>
            <div class="my-card card text-center col-sm-6 col-md-4 col-lg-3">
                <i class="fa-solid fa-graduation-cap"></i>
                <div class="card-body text-white">
                    <h5 class="card-title">Education</h5>
                    <p class="card-text">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <a href="#" class="btn my-btn text uppercase">Learn more</a>
                </div>
            </div>
            <div class="my-card card text-center col-sm-6 col-md-4 col-lg-3">
                <i class="fa-brands fa-pagelines"></i>
                <div class="card-body text-white">
                    <h5 class="card-title">Farming</h5>
                    <p class="card-text">Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.</p>
                    <a href="#" class="btn my-btn text uppercase">Learn more</a>
                </div>
            </div>
        </div>

        

    </div>
    
  </section>
</template>

<style lang="scss" scoped>

section{
    width: 100%;
    background-image: url('https://avada.website/charity/wp-content/uploads/sites/72/2016/08/home-content-bg-2.jpg');
    background-size: cover;
    background-position: bottom;

    .values-container{

        width: 80%;
        margin: 0 auto;
        padding-top: 200px;

        div{

            h2{

                font-size:50px;
            }

            .line{

                background-color: $my-yellow;
                width: 200px;
                height: 2px;
                margin-left:calc(50% - 100px);
            }

            span{
                font-size: 25px;
            }
        }
    }

    .my-row{

        padding: 100px 0;
        .my-card{
            background:none;
            border: none;
            i{
                font-size: 100px;
                color: $my-yellow;
                &:hover{
                    color: white;
                }
            }
            .my-btn{
                background-color: $my-yellow;
                color: white;
                padding: 10px 30px;
                &:hover{
                    background-color: $my-dark-blue;
                }
            }
        }
    }
  }
  

</style>
