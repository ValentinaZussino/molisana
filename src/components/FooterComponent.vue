<template>
    <footer>
        <div class="cols container">
            <a href="#" class="logo">
                <img src="../assets/img/la-molisana-logo.png" alt="La Molisana">
            </a>
            <div class="footer-links">
            </div>
            <div class="footer-links">
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        name: 'FooterComponent'
    }
</script>

<style lang="scss" scoped>
@use '../assets/styles/partials/mixin' as *;
@use '../assets/styles/partials/variables' as *;

footer {
    padding-top: 3rem;
    .cols {
        display: flex;
        margin-bottom: 3rem;

        .logo, footer-links {
            flex-basis: calc(100% / 3);
            padding: 0 1rem;
        }
    }
}

</style>