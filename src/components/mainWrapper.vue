<template>
    <div class="mainWrapper">
        <div class="mainWrapper__left">
            <img href="#!" src="../static/mainWrapper__left.svg" alt="mainWrapper" class="mainWrapper-photo" />
        </div>
        <div class="mainWrapper__right">
            <div class="mainWrapper__right-top">
                <p class="mainWrapper__right-top-top-item">
                    We focus on ergonomics
                </p>
                <p class="mainWrapper__right-top-bottom-item">
                    Most calendars are designed for teams.
                    Slate is designed for freelancers
                </p>
            </div>
            <div class="mainWrapper__right-bottom">

            </div>
        </div>
    </div>
</template>

<script>

import "@fontsource/roboto";

export default {
    name: 'mainWrapper',
}
</script>
  
<style>
.mainWrapper {
    display: flex;
}

.mainWrapper__right {
    margin-top: 100px;
}

.mainWrapper__right-top-top-item {
    color: #FFF;
    font-family: Roboto;
    font-size: 55px;
    font-style: normal;
    font-weight: 900;
    line-height: 65.5px;
    letter-spacing: 0.2px;
}

.mainWrapper__right-top-bottom-item {
    color: #FFF;
    font-family: Roboto;
    font-size: 16px;
    font-style: normal;
    font-weight: 700;
    line-height: 20px;
    letter-spacing: 0.2px;
    width: 300px;
}

@media (max-width: 375.98px) {
    .mainWrapper {
        flex-direction: column-reverse;
    }

    .mainWrapper-photo {
        width: 375px;
        margin-left: 0;
    }

    .mainWrapper__right-top {
        margin: -139px 55px -14px 32px;
    }

    .mainWrapper__right-top-top-item {
        color: var(--Light-text, #FFF);
        text-align: center;
        /* H2 */
        font-family: Roboto;
        font-size: 46px;
        font-style: normal;
        font-weight: 400;
        line-height: 57px;
        /* 123.913% */
        letter-spacing: 0.2px;
    }

    .mainWrapper__right-top-bottom-item {
        color: var(--Light-text, #FFF);
        text-align: center;
        /* H4 */
        font-family: Roboto;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: 20px;
        /* 125% */
        letter-spacing: 0.2px;
    }
}</style>
