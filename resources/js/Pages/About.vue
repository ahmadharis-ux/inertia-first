<template>
    <Layout title="About">
        <hr>
        <h1>{{title}}</h1>
        <div class="card">
            <div class="card-body">
                <p>{{ deskripsi }} Ini Di Halaman About</p>
            </div>
            <Link href="/home" as="button" type="button">Home</Link>
        </div>
    </Layout>
</template>

<script>
import { Link } from '@inertiajs/vue3'
import Layout from '../Shared/Layouts.vue'
    export default {
        props: ['deskripsi','title'],
        components: {
                Link,
                Layout,
            }
    }
</script>