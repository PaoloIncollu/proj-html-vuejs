<script>
export default {
  data() {
    return {
        cards:[
            {
                id:'1',
                title:'Fair trade',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/avada-charity-fair-trade-featured.jpg'
            },
            {
                id:'2',
                title:'Shelter',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/avada-charity-shelter-featured.jpg'
            },
            {
                id:'3',
                title:'Farming',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/avada-charity-farming-featured.jpg'
            },
            {
                id:'4',
                title:'Vaccines',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/avada-charity-vaccines-featured.jpg'
            }

        ]
      
    }
  }
}
</script>

<template>
  <section>
    <div class="causes-container">

        <div class="text-center">
            <h2 class="text-uppercase">
                Recent Causes
            </h2> 
            
            <div class="line my-5">

            </div> 

            
            <span>
                We run projects in over 30 countries in 5 contintents
            </span>
            
        </div>

        <div class="my-row row">

            <div v-for="(card,i) in this.cards" :key="i" class="my-card card col-sm-6 col-md-4 col-lg-3">

                <div  class="container-card">

                <div class="my-img-card">
                    <img :src="card.img"  alt="...">    
                </div>

                <div class="card-hover card text-uppercase ">

                    <h4 class="text-center text-white text-uppercase">

                        {{card.title}}

                    </h4>

                </div>    
            </div>
                
            
            
            </div>
            
        </div>

    </div>

    <div class="bottom-section p-5">
        <h4 class="text-center p-2">
            <a href="#" class="text-uppercase">
                View all our causes
            </a>
        </h4>
    </div>
  </section>
</template>

<style lang="scss" scoped>

section{
    position: relative;
    width: 100%;
    background-color: white;

    .causes-container{

        width: 80%;
        margin: 0 auto;
        padding-top: 100px;
        

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
        .my-row{

            padding: 100px 0 200px;

            .my-card{
                
                background:none;
                border: none;
                margin-bottom: 10px;

                .container-card{

                    position: relative;

                    img{
                    border-radius: 5px;
                    width: 100%;
                    height: 100%;
                    display: block;
                    
                    }
                

                    .card-hover{

                        display: none;
                        position: absolute;
                        top: 0;
                        left: 0;
                        width: 100%;
                        height: 100%;
                        

                        h4{
                            margin-top:calc(50% - 50px);
                            line-height: 20px;
                            
                        }
                    
                        
                    }
                    
                    &:hover .card-hover{

                        display: block;
                        align-items: center;
                        background-color: rgba($color: $my-yellow, $alpha: 0.7);
                    }
                
                

                }
                

            }
        }
    }
    
    .bottom-section{
        position: absolute;
        bottom: 0;
        left: 0;
        background-color: #ED6967;
        width: 100%;

        &:hover{

            background-color: #408292;
        }

        h4{
            width: 100%;
            a{
                width: 100%;
                color: white;
                text-decoration: none;

            }
        }

    }

}
  
  

</style>
