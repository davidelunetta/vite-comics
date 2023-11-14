<template>
    <div class="blue">
        <div class="inner-buy">

            <div class="item">
                <img src="@/assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>

            <div class="item">
                <img src="@/assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>

            <div class="item">
                <img src="@/assets/img/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>

            <div class="item">
                <img src="@/assets/img/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>

            <div class="item">
                <img src="@/assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .blue{
        height: 150px;
        background-color: #0282F9;
        display: flex;
        align-items: center;

        .inner-buy{
            width: 1300px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;

            .item{
                display: flex;
                align-items: center;
                color: #fff;
                padding: 0;

                img{
                    width: 50px;
                    margin-right: 10px;
                }
            }
        }
    }
</style>