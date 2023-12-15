<template>
    <div class="upperFooterWrapper">
        <div class="upperFooter__main">
            <div class="upperFooter__main-top">
                <p class="upperFooter__main-top-top-item">
                    Lightning fast prototyping
                </p>
                <p class="upperFooter__main-top-bottom-item">
                    Most calendars are designed for teams. Slate is designed for freelancers
                </p>
            </div>
            <div class="upperFooter__main-bottom">
                <div class="upperFooter__main-bottom-item">
                    Try For Free
                </div>
            </div>
        </div>
    </div>
</template>
   
<script>


export default {
    name: 'upperFooter',
}
</script>
     
<style>
.upperFooterWrapper {
    margin-bottom: 138px;
}

.upperFooter__main-top {
    width: 300px;
    margin: 100px 0 0 610px;
}

.upperFooter__main-top-top-item {
    color: #252B42;
    text-align: center;
    font-family: Roboto;
    font-size: 46px;
    font-style: normal;
    font-weight: 400;
    line-height: 57px;
    letter-spacing: 0.2px;
}

.upperFooter__main-top-bottom-item {
    color: #374754;
    text-align: center;
    font-family: Roboto;
    font-size: 16px;
    font-style: normal;
    font-weight: 700;
    line-height: 20px;
    letter-spacing: 0.2px;
}

.upperFooter__main-bottom {
    padding: 16px;
    background-color: #38A3F1;
    width: 236px;
    height: 36px;
    border-radius: 35px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 70px 0 0 630px;
}

.upperFooter__main-bottom-item {
    color: #FFF;
    font-family: Roboto;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 33px;
    letter-spacing: 0.1px;
}

@media (max-width: 375.98px) {
    .upperFooterWrapper {
        margin-bottom: 42px;
    }
    .upperFooter__main-top {
        margin: 100px 0 0 40px;
    }
    .upperFooter__main-bottom {
        margin: 37px 0 0 60px;
    }
}
</style>
   