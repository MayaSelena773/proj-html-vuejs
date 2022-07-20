<template>
<!--Sezione risorse-->
    <section class="bg-antique">
        <div class="between">
            <div class="resource-box">
                <h3 class="med-title padd-right">Marketing Resources: Insider Advice on How to Increase Online Sales</h3>
            </div>
            <div class="resource-box self">
                <span class="button btn-orange padd-btn">Explore All Resources</span>
            </div>
        </div>
        <div class="flex">
            <div class="card-resource">
                <img src="../assets/img/blog-posts-6-200x133.jpg" alt="blog6" class="blog-img">
                <p class="large-text padd">Marketing Tips and Tricks For Your Website</p>
            </div>
            <div class="card-resource">
                <img src="../assets/img/blog-posts-5-200x133.jpg" alt="blog5" class="blog-img"> 
                <p class="large-text">How to Write Stunning Blog Post Titles</p>
            </div>
            <div class="card-resource">
                <img src="../assets/img/blog-posts-4-200x133.jpg" alt="blog4" class="blog-img"> 
                <p class="large-text">Tecniques to Reduce Facebook Ads Spend</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'PageResources'
}
</script>

<style lang="scss" scoped>

.bg-antique {
    background-color: rgb(244, 243, 246);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

    .between {
        width: 70%;
        display: flex;
        justify-content: space-between;
    }
    .resource-box {
        //width: 50%;
    } 
    .padd-right {
        padding: 6rem 0;
        padding-right: 500px;
    }
    .self {
        width: 300px;
        align-self: flex-end;
        padding-bottom: 100px;
    }
    
    .card-resource {
        width: 350px;
        margin: 2rem;

        .blog-img {
            width: 100%;
        }
    }  
}
</style>


