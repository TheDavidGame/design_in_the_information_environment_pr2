<template>
    <div class="footerWrapper">
        <div class="footerWrapper__main-top">
            <p class="footerWrapper__main-top-top">
                At your fingertips
            </p>
            <p class="footerWrapper__main-top-bottom">
                Lightning fast prototyping
            </p>
        </div>
        <div class="footerWrapper__main-bottom">
            <p class="footerWrapper__main-bottom-top">
                Subscribe to our Newsletter
            </p>
            <p class="footerWrapper__main-bottom-bottom">
                Available exclusivery on Figmaland
            </p>
        </div>
        <div class="footerWrapper__main-bottom-btn">
            <div class="footerWrapper__main-bottom-btn-item">
                Subscribe
            </div>
        </div>
    </div>
</template>
   
<script>


export default {
    name: 'footerWrapper',
}
</script>
     
<style>
.footerWrapper {
    background: var(--Background-Gradient, linear-gradient(40deg, #EF2779 0.79%, #7834BE 79.29%));
    height: 505px;
}

.footerWrapper__main-top {
    padding: 60px 0 0 0;
}

.footerWrapper__main-top-top {
    color: #FFF;
    text-align: center;
    font-family: Roboto;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 33px;
    letter-spacing: 0.1px;
    margin-bottom: -20px;
}

.footerWrapper__main-top-bottom {
    color: #FFF;
    text-align: center;
    font-family: Roboto;
    font-size: 46px;
    font-style: normal;
    font-weight: 400;
    line-height: 57px;
    letter-spacing: 0.2px;
}

.footerWrapper__main-bottom {
    margin: 0 0 0 620px;
}

.footerWrapper__main-bottom-top {
    color: #FFF;
    font-family: Roboto;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 33px;
    letter-spacing: 0.1px;
}

.footerWrapper__main-bottom-bottom {
    color: #FFF;
    font-family: Roboto;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 27px;
    letter-spacing: 0.2px;
}

.footerWrapper__main-bottom-btn {
    border-radius: 35px;
    background: #EF2779;
    width: 353px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 0 0 590px;
}

.footerWrapper__main-bottom-btn-item {
    color: #FFF;
    font-family: Roboto;
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
    line-height: 16px;
    letter-spacing: 0.2px;
}

@media (max-width: 375.98px) {
    .footerWrapper {
        background: var(--Background-Gradient, linear-gradient(40deg, #EF2779 0.79%, #7834BE 79.29%));
        height: 514px;
    }
    .footerWrapper__main-bottom-btn {
        margin: 0 0 0 11px;
    }
    .footerWrapper__main-bottom {
        margin: -5px 0 38px 50px;
    }
}
</style>
   