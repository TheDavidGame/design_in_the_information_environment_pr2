<template>
    <header class="header">
        <div class="header__wrapper">
            <div class="header__logo">
                <img href="#!" src="../static/logo.svg" alt="header_logo" class="header__logo" />
            </div>
            <nav class="header__nav">
                <ul class="header__list">
                    <li class="header__item">
                        <p class="header__item-text">
                            Home
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            Product
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            Pricing
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            About
                        </p>
                    </li>
                    <li class="header__item">
                        <p class="header__item-text">
                            Contact
                        </p>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>

import "@fontsource/roboto";

export default {
    name: 'headerMain',
}
</script>
  
<style>
.header__wrapper {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 20px;
}


.header__list {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}

.header__item {
    list-style-type: none;
    margin-right: 32px;
}


.header__item-text {
    color: #FFF;
    text-align: center;
    font-family: Roboto;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 27px;
    letter-spacing: 0.2px;
}

@media screen and (max-width: 375px) {}
</style>
