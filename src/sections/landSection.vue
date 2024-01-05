<script setup lang='ts'>
</script>

<template>
    <section class="landSection">
        <div class="header">
            <div class="logo">
                <img src="../assets/rg.svg" alt="RG Logo">
                <h1><span>R</span>ivers <span>G</span>rove</h1>
            </div>
            <div class="contact">
                <button class="contactButton">
                    <i class="fa-solid fa-phone"></i>
                </button>
                <button class="contactButton">
                    <i class="fa-duotone fa-envelope"></i>&nbsp;
                </button>
                <button>
                    <i class="fa-solid fa-user"></i>
                </button>
                <button>
                    <i class="fa-solid fa-earth-americas"></i>
                </button>
            </div>
        </div>
    </section>
</template>

<style>

.landSection {
    width: 100vw;
    height: 100vh;
    background-color: #F9F9FA;
    & .header {
        box-sizing: border-box;
        width: 100%;
        height: 6rem;
        background-color: #F9F9FA;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-left: 4rem;
        & .logo {
            width: fit-content;
            height: 4rem;
            display: flex;
            align-items: center;
            text-wrap: nowrap;
            gap: 1rem;
            & img {
                width: 100%;
                height: 40%;
            }
        }
        h1 {
            margin: 0;
            color: #C0C0C0;
            font-size: 1.2rem;
            & span {
                color: #a8c3f5;
            }
        }
        & .contact {
            & button {
                height: 2rem;
                aspect-ratio: 1;
                background-color: #809bcd;
                border: none;
                border-radius: 50%;

            }
            i {
                color: #fff;
            }
        }
    }

    @media (orientation: portrait) {
        & .header {
            padding-left: 2rem;
        }
    }
}
</style>