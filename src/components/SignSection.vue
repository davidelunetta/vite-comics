<template>
    <div class="box">
         <div class="sign-up">
             <button>SIGN-UP NOW!</button>
         </div>
         <div class="follow-us">
             <h2>FOLLOW US</h2>
             <img src="@/assets/img/footer-facebook.png" alt="">
             <img src="@/assets/img/footer-twitter.png" alt="">
             <img src="@/assets/img/footer-youtube.png" alt="">
             <img src="@/assets/img/footer-periscope.png" alt="">
             <img src="@/assets/img/footer-pinterest.png" alt="">
         </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.box{
    display: flex;
    justify-content: space-around;
    height: 110px;
    background-color: #303030;

    .follow-us{
        display: flex;
        width: 500px;
        align-items: center;
        color: #076CC9;

        img{
            height: 35px;
            margin-left: 25px;
            cursor: pointer;
        }
    }

    .sign-up{
        display: flex;
        align-items: center;
        button{
            border: 2px solid #037AE8;
            padding: 20px;
            background-color: #303030;
            color: #fff;
            font-weight: bold;
            font-size: 20px;
            width: 200px;
            cursor: pointer;
        }
    }

}

</style>