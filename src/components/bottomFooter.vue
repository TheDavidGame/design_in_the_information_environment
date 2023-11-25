<template>
    <div class="bottomFooter__wrapper">
        <div class="bottomFooter__top">
            <div class="bottomFooter__top-left">
                <div class="bottomFooter__top-left-littleText">
                    <p class="bottomFooter__top-left-littleText-item">
                        Get in touch
                    </p>
                </div>
                <div class="bottomFooter__top-left-mainText">
                    <p class="bottomFooter__top-left-mainText-item">
                        Think we would be a good fit for your next project?
                    </p>
                </div>
            </div>
            <div class="bottomFooter__top-right">
                <p class="bottomFooter__top-right-item">
                    Get in touch
                </p>
            </div>
        </div>
        <div class="bottomFooter__bottom">
            <div class="bottomFooter__bottom-left">
                <div class="bottomFooter__bottom-left-mainText">
                    <img src="../static/bottomFooter__bottom-left-mainText-item.svg"
                        alt="bottomFooter__bottom-left-mainText-item" class="bottomFooter__bottom-left-mainText-item" />
                </div>
                <div class="bottomFooter__bottom-left-littleText">
                    <p class="bottomFooter__bottom-left-littleText-item">
                        Powered by Webflow.
                    </p>

                    <p class="bottomFooter__bottom-left-littleText-item">

                        All rights reserved Wishbone+Partners, Inc. Licensing.
                    </p>
                </div>
            </div>
            <div class="bottomFooter__bottom-right">
                <div class="bottomFooter__bottom-right">
                    <img src="../static/bottomFooter__bottom-right-item.svg" alt="bottomFooter__bottom-right-item"
                        class="bottomFooter__bottom-right-item" />
                </div>
            </div>
        </div>
    </div>
</template>
  
<script>
import "@fontsource/poppins";

export default {
    name: 'bottomFooter',
}
</script>
  
<style>
p {
    margin: 0;
    padding: 0;
}

.bottomFooter__top {
    background: #CEC4BC;
    height: 314px;
    display: flex;
    align-items: center;
}

.bottomFooter__top-left {
    padding: 100px 447px 100px 136px;
    width: 569px;
}

.bottomFooter__top-right {
    padding: 32px 0 0 0;
}

.bottomFooter__top-left-littleText-item {
    color: #645C55;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    letter-spacing: 2px;
    text-transform: uppercase;
}

.bottomFooter__top-left-mainText-item {
    color: #1B1A1A;
    font-family: Poppins;
    font-size: 40px;
    font-style: normal;
    font-weight: 400;
    line-height: 42px;
}

.bottomFooter__top-right-item {
    color: #1B1A1A;
    font-family: Poppins;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 24px;
    /* 150% */
    letter-spacing: 0.4px;
}

.bottomFooter__bottom {
    height: 204px;
    display: flex;
    align-items: center;
}

.bottomFooter__bottom-left {
    padding: 60px 609px 60px 136px;
}

.bottomFooter__bottom-left-littleText {
    padding-top: 20px;
}

.bottomFooter__bottom-left-littleText-item {
    color: #645C55;
    font-family: Poppins;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
}

@media screen and (max-width: 376px) {
    .bottomFooter__top-left {
        padding: 101px 0 100px 8px;
    }

    .bottomFooter__top-left-littleText-item {
        font-size: 12px;
    }

    .bottomFooter__top-left-mainText-item {
        font-size: 20px;
        line-height: 25px;
    }

    .bottomFooter__bottom-left {
        padding: 60px 4px 60px 14px;
    }

    .bottomFooter__top {
        height: 161px;
    }

    .bottomFooter__top-right {
        padding: 0 0 0 0;
    }

    .bottomFooter__top-right-item {
        font-size: 15px;
        line-height: 20px;
    }

    .bottomFooter__bottom-left-mainText-item {
        width: 156px;
    }

    .bottomFooter__bottom-left-littleText {
        padding-top: 7px;
    }

    .bottomFooter__bottom-left-littleText-item {
        font-size: 10px;
        line-height: 15px;
    }

    .bottomFooter__bottom-right-item {
        width: 100px;
    }
}
</style>
  