<template>
    <Header/>
    <div class="container-fluid">
        <div class="row">
            <div class="col-sm-3">
                SIDEBAR
            </div>
            <div class="col-sm-9">
                CONTENT
                <router-view></router-view>
            </div>
        </div>
    </div>
</template>
<script>
    import Header from '../components/Header.vue';
    export default {
        components: {
            Header
        }
    }
</script>
