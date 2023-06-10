<script>
import {Link} from '@inertiajs/vue3'
import Layout from '../Shared/Layouts.vue'
export default {
        props: ['title'],
        components:{
            Link,
            Layout,
        },
    }
</script>

<template>
    <Layout>
        <hr>
        <h1>Hello {{ title }}! Ini di halaman Home</h1>
        <Link href="/about">About</Link>
    </Layout>
</template>

<style>

</style>

