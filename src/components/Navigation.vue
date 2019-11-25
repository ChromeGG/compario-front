<template>
    <mdb-navbar position="top" dark color="purple-gradient" scrolling>
        <mdb-navbar-brand href="#"><img src="/src/assets/logo-icon.png" alt="logo-icon"></mdb-navbar-brand>
        <mdb-navbar-toggler>
            <mdb-navbar-nav>
                <mdb-nav-item href="#" waves-fixed>Home</mdb-nav-item>
                <mdb-nav-item href="#" waves-fixed>Features</mdb-nav-item>
                <mdb-nav-item href="#" waves-fixed>Pricing</mdb-nav-item>
                <!-- Dropdown -->
                <mdb-dropdown tag="li" class="nav-item">
                    <mdb-dropdown-toggle tag="a" navLink slot="toggle" waves-fixed>Dropdown</mdb-dropdown-toggle>
                    <mdb-dropdown-menu>
                        <mdb-dropdown-item>Action</mdb-dropdown-item>
                        <mdb-dropdown-item>Another action</mdb-dropdown-item>
                        <mdb-dropdown-item>Something else here</mdb-dropdown-item>
                    </mdb-dropdown-menu>
                </mdb-dropdown>
            </mdb-navbar-nav>
            <!-- Search form -->

        </mdb-navbar-toggler>
    </mdb-navbar>
</template>

<script>
    import {
        mdbBtn,
        mdbDropdown,
        mdbDropdownItem,
        mdbDropdownMenu,
        mdbDropdownToggle,
        mdbInput,
        mdbNavbar,
        mdbNavbarBrand,
        mdbNavbarNav,
        mdbNavbarToggler,
        mdbNavItem
    } from 'mdbvue';

    export default {
        name: 'NavigationPage',
        components: {
            mdbNavbar,
            mdbNavItem,
            mdbNavbarNav,
            mdbNavbarToggler,
            mdbDropdown,
            mdbDropdownItem,
            mdbDropdownMenu,
            mdbDropdownToggle,
            // eslint-disable-next-line vue/no-unused-components
            mdbInput,
            // eslint-disable-next-line vue/no-unused-components
            mdbBtn,
            mdbNavbarBrand
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .view {
        background: url("https://mdbootstrap.com/img/Photos/Others/img (42).jpg") no-repeat center center;
        background-size: cover;
        height: 100%;
    }

    .navbar .dropdown-menu a:hover {
        color: inherit !important;
    }
</style>

