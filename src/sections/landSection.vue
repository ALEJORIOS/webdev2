<script setup lang='ts'>
</script>

<template>
    <section class="landSection">
        <div class="header">
            <div class="logo">
                <img src="../assets/rg.svg" alt="RG Logo">
                <h1>hod</h1>
            </div>
            <div class="options">
                <!-- <button class="contactButton">
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
                </button> -->
                <button class="contact">Contacto</button>
                <button class="menu">Menú</button>
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
        padding: 0 4rem;
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
            font-size: 2rem;
            font-family: 'roundo';
            & span {
                color: #a8c3f5;
            }
        }
        & .options {
            display: flex;
            gap: 1rem;
            & button {
                cursor: pointer;
            }
            & .contact {
                border: 2px solid #a8c3f5;
                background-color: #fff;
                height: 2.5rem;
                padding: 0 1rem;
                border-radius: 1.2rem;
                color: #7fa2e2;
            }

            & .menu {
                border: 2px solid #a8c3f5;
                background-color: #fff;
                height: 2.5rem;
                padding: 0 1rem;
                border-radius: 1.2rem;
                color: #7fa2e2;
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