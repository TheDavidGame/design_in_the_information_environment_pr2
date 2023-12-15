<template>
    <div class="underMainWrapper">
        <div class="underMainWrapper-main">
            <div class="underMainWrapper-main-top">
                <p class="underMainWrapper-main-top-item1">
                    At your fingertips
                </p>
                <p class="underMainWrapper-main-top-item2">
                    Features
                </p>
                <p class="underMainWrapper-main-top-item3">
                    Most calendars are designed for teams.
                    Slate is designed for freelancers
                </p>
            </div>
            <div class="underMainWrapper-main-bottom">
                <div class="underMainWrapper-main-bottom-list">
                    <div class="underMainWrapper-main-bottom-item">
                        <div class="underMainWrapper-main-bottom-item-group">
                            <div class="underMainWrapper-main-bottom-item-photo">
                                <img href="#!" src="../static/underMain1.svg" alt="underMainWrapper-main-bottom-item-photo"
                                    class="underMainWrapper-main-bottom-item-photo" />
                            </div>
                            <p class="underMainWrapper-main-bottom-item-photo-text">
                                The best products start with Sketch
                            </p>
                        </div>

                        <p class="underMainWrapper-main-bottom-item-text">
                            Slate helps you see how many more days you need to work to reach your financial goal.
                        </p>
                    </div>
                    <div class="underMainWrapper-main-bottom-item">
                        <div class="underMainWrapper-main-bottom-item-group">
                            <div class="underMainWrapper-main-bottom-item-photo">
                                <img href="#!" src="../static/underMain2.svg" alt="underMainWrapper-main-bottom-item-photo"
                                    class="underMainWrapper-main-bottom-item-photo" />
                            </div>
                            <p class="underMainWrapper-main-bottom-item-photo-text">
                                Fastest way to organize
                            </p>
                        </div>

                        <p class="underMainWrapper-main-bottom-item-text">
                            Slate helps you see how many more days you need to work to reach your financial goal.
                        </p>
                    </div>
                    <div class="underMainWrapper-main-bottom-item">
                        <div class="underMainWrapper-main-bottom-item-group">
                            <div class="underMainWrapper-main-bottom-item-photo">
                                <img href="#!" src="../static/underMain3.svg" alt="underMainWrapper-main-bottom-item-photo"
                                    class="underMainWrapper-main-bottom-item-photo" />
                            </div>
                            <p class="underMainWrapper-main-bottom-item-photo-text">
                                Work better together
                            </p>
                        </div>

                        <p class="underMainWrapper-main-bottom-item-text">
                            Slate helps you see how many more days you need to work to reach your financial goal.
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="underMainWrapper-underMain">

        </div>
    </div>
</template>
   
<script>

export default {
    name: 'underMainWrapper',
}
</script>
     
<style>
.underMainWrapper {
    margin-top: 200px;
}


.underMainWrapper-main-top {
    width: 320px;
    margin: 0 0 50px 600px;
}

.underMainWrapper-main-top-item1 {
    color: #252B42;
    text-align: center;
    font-family: Roboto;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 33px;
    letter-spacing: 0.1px;
}

.underMainWrapper-main-top-item2 {
    color: #252B42;
    text-align: center;
    font-family: Roboto;
    font-size: 46px;
    font-style: normal;
    font-weight: 400;
    line-height: 57px;
    letter-spacing: 0.2px;
}

.underMainWrapper-main-top-item3 {
    color: #374754;
    text-align: center;
    font-family: Roboto;
    font-size: 16px;
    font-style: normal;
    font-weight: 700;
    line-height: 20px;
    letter-spacing: 0.2px;
}

.underMainWrapper-main-bottom-list {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}

.underMainWrapper-main-bottom-item {
    margin: 0 52px 0 52px;
}

.underMainWrapper-main-bottom-item-group {
    display: flex;
    flex-wrap: nowrap;
    justify-content: space-between;
    align-items: center;
}

.underMainWrapper-main-bottom-item-photo-text {
    color: #252B42;
    font-family: Roboto;
    font-size: 22px;
    font-style: normal;
    font-weight: 700;
    line-height: 33px;
    letter-spacing: 0.1px;
    width: 187px;
}

.underMainWrapper-main-bottom-item-text {
    color: #374754;
    font-family: Roboto;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 27px;
    letter-spacing: 0.2px;
    width: 255px;
}

@media (max-width: 375.98px) {
    .underMainWrapper {
        margin-top: -72px;
    }
    .underMainWrapper-main-top {
        width: 317px;
        margin: 0 0 74px 40px;
        padding-top: 63px;
    }
}
</style>
   