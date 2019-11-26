<template>
    <mdb-navbar position="top" dark color="purple-gradient" scrolling>
        <mdb-navbar-brand href="#"><img src="../assets/logo-icon.png" alt="logo-icon"></mdb-navbar-brand>
        <mdb-navbar-toggler class="d-flex justify-content-end">
            <div>
                <mdb-navbar-nav>
                    <mdb-nav-item href="#" waves-fixed>Login <img src="../assets/login-icon.png" alt="login-icon">
                    </mdb-nav-item>
                </mdb-navbar-nav>
            </div>
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

</style>

