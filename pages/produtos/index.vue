<template>
   
    <div>
        <div class="container mx-auto">
            <h1 class="text-lg font-bold">Produtos</h1>
            <NuxtLink to="/produtos/produto-a">Produto A</NuxtLink>
            <NuxtLink to="/produtos/produto-b">Produto B</NuxtLink>

            <br/>
            <br/>

            <div v-for="product in products" :key="product.id" class="border-b border-400 py-3">
                {{ product.title }}
            </div>

            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloribus tempore non accusamus, 
            </p>
        </div>
    </div>
  
</template>

<script>


export default {
    name: '',

    data() {
        return {

        };
    },

    async asyncData({ $axios }) {
         const products = await $axios.$get('posts?_limit=3')
         return {
           products,
         }
       },

    methods: {},

}
</script>

<style>

</style>