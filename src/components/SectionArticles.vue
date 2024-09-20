<script>
export default {
  data() {
    return { 
        articles:[
            {
                id:'1',
                title:'The Human Story Of Uniqueness',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/photo-1444664597500-035db93e2323-200x150.jpg',
                text:'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Prasent ac nibh vestibulum, laoreet ipsum.'
            },
            {
                id:'2',
                title:'Sustainable Trade Tactics',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/photo-1447430617419-95715602278e-200x150.jpg',
                text:'Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.'
            },
            {
                id:'3',
                title:'Farmers Making A Difference',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/photo-1460230525622-630fe3294cd7-200x150.jpg',
                text:'Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.'
            },
            {
                id:'4',
                title:'Meeting Remote Tribes In Peru',
                img:'https://avada.website/charity/wp-content/uploads/sites/72/2016/08/photo-1460600421604-5e138c208b9c-200x150.jpg',
                text:'Nullam convallis, orci in congue aliquet, diam mauris cursus urna, Id maximus lectus magna maximus.'
            }

        ]
      
      
    }
  }
}
</script>

<template>
  <section>
    <div class="text-center">

        <h2 class="text-uppercase">
            Latest Articles
        </h2>

        <div class="line my-4">

        </div>

        <span>
            Toghether we make all the difference
        </span>    
    </div>

    <div class="my-row d-flex flex-wrap">

        <div class="col-sm-12 col-md-12 col-lg-6 pb-5 pe-3">
            <div class="card">
                <img src="../pubblic/img/HelloIMG1669149322752.jpeg" class="card-img-top" alt="...">
                <div class="card-body pt-5">
                    <h3 class="card-title">
                        <a href="#">
                            Understanding community complexities
                        </a>
                    </h3>
                    <p class="card-text py-4 lh-1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Prasent ac nibh vestibulum, laoreet ipsum.</p>
                    <a href="#">Read More</a>
                </div>
            </div>
        </div>

        <div class="col-sm-12 col-md-12 col-lg-6 right">

            <div v-for="(article,i) in this.articles" :key="i" class="d-flex mb-5">

                <div class="me-5 w-25">
                    <img :src="article.img" alt="">
                </div>
                <div>
                    <h3>
                        <a href="#">
                            {{article.title}}
                        </a>
                        
                    </h3>

                    <span>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Prasent ac nibh vestibulum, laoreet ipsum.
                    </span>
                </div>
            </div>
            
        </div>


    </div>
    
    <div class="footer">
        <h3 class="text-center py-4">
            <a href="#" class="text-center text-uppercase text-white text-decoration-none">
                View all our articles
            </a>
        </h3>
    </div>
  </section>
</template>

<style lang="scss" scoped>

section{

    width: 100%;
    background-color: white;
    padding: 100px 0;

    div{

        h2{

            font-size: 40px;
        }

        .line{

            background-color: $my-yellow;
            width: 200px;
            height: 2px;
            margin-left: calc(50% - 100px);
        }     

        span{
            font-size: 20px;
        }
    }

    .my-row{

        width: 80%;
        margin: 0 auto;
        padding: 100px 0;

        h3{
            a{

                color: $my-yellow; 
                text-decoration: none;    
            }
            
        }

        a{
            font-weight: bolder;
            color: black;
        }

        .right{


            img{
                width: 150px;
                height: 150px;
                object-fit: cover;
            }
        }
    }

    .footer{

        width: 80%;
        margin: 0 auto;
        background-color: $my-light-coral;
    }
    
    
  }

  

</style>
