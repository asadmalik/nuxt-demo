<template>
    <div>
        <h1>Single Blog Page</h1>
        <p>
            Blog Post: {{ route.params.slug }}
        </p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magni veritatis, accusamus, totam reiciendis sed
            eos dolores eum, fugit eveniet quae consequuntur. Neque, illum minus? Cumque, ex ipsam. Voluptatum, odio
            quae.</p>
        <div style="font-family: monospace; margin-top: 3rem; padding: 20px">
            Path: {{ route.params.slug }}
        </div>
    </div>
</template>
<script setup>

    const route = useRoute()

</script>