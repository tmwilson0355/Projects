<script setup>
import {useRouter} from 'vue-router';

const router = useRouter()

function goToProductsPage() {
    router.push('/products')
}

</script>

<template>
    <body>
         <h1>Welcome to our website!</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quibusdam illum officiis iusto aut sapiente ducimus error laudantium doloribus nostrum modi? Iure odio ipsa doloribus, labore reprehenderit itaque atque illum dolor, error corrupti eveniet velit totam tempore quas ratione facilis architecto debitis aliquid quibusdam. Illum nostrum commodi quae, minus officia reprehenderit vero fuga error alias quas in iure distinctio est optio?</p>
    </body>
    <button @click="goToProductsPage()">View Products</button>
</template>

<style scoped>
    body {
        text-align: center;
    }
</style>