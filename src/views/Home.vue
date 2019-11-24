<template>
    <mdb-row>
        <mdb-col md="12">
            <mdb-navbar color="purple-gradient" class="lighten-3 py-4 mb-4">
                <mdb-navbar-nav nav class="font-weight-bold">
                    <mdb-nav-item href="#" active anchorClass="white-text">Active</mdb-nav-item>
                    <mdb-nav-item href="#" anchorClass="white-text">Link</mdb-nav-item>
                    <mdb-nav-item href="#" anchorClass="white-text">Link</mdb-nav-item>
                    <mdb-nav-item href="#" anchorClass="white-text">Link</mdb-nav-item>
                </mdb-navbar-nav>
            </mdb-navbar>
        </mdb-col>
    </mdb-row>
</template>

<script>
    import {mdbCol, mdbNavbar, mdbNavbarNav, mdbNavItem, mdbRow} from 'mdbvue';

    export default {
        name: 'home',
        components: {
            mdbNavbar,
            mdbNavbarNav,
            mdbNavItem,
            mdbRow,
            mdbCol
        }
    }
</script>

<style>
    .nav a.white-text:hover {
        color: #e0e0e0 !important;
    }
</style>
