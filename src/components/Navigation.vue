<template>
    <mdb-navbar color="purple-gradient" dark position="top">
        <mdb-navbar-brand>
            <img src="../assets/logo-icon.png" alt="logo-icon">
        </mdb-navbar-brand>
        <mdb-navbar-toggler>
            <mdb-navbar-nav>
                <mdb-nav-item href="#" active>Home</mdb-nav-item>
                <mdb-nav-item href="#">Features</mdb-nav-item>
                <mdb-nav-item href="#">Pricing</mdb-nav-item>
            </mdb-navbar-nav>
            <form class="white-text">
                Login <img src="../assets/login-icon.png" alt="login-icon">
            </form>
        </mdb-navbar-toggler>
    </mdb-navbar>
</template>

<script>
    import {mdbNavbar, mdbNavbarBrand, mdbNavbarNav, mdbNavbarToggler, mdbNavItem} from 'mdbvue';

    export default {
        name: 'NavigationPage',
        components: {
            mdbNavbar,
            mdbNavItem,
            mdbNavbarNav,
            mdbNavbarToggler,
            mdbNavbarBrand
        }
    }
</script>

<style scoped>

    .navbar .dropdown-menu a:hover {
        color: inherit !important;
    }

    template {
        margin-bottom: 100px;
    }

</style>

