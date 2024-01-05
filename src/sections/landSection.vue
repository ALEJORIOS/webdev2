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
                <i class="fa-duotone fa-phone-volume"></i>&nbsp;
                <span>+57 322 7866582</span>
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
            i {
                color: #809bcd;
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