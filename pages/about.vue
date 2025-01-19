<template>
    <div>
        <h1>About Page</h1>
        <p>
            Staic page for <code>/about/</code>
        </p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Magni veritatis, accusamus, totam reiciendis sed
            eos dolores eum, fugit eveniet quae consequuntur. Neque, illum minus? Cumque, ex ipsam. Voluptatum, odio
            quae.</p>
        <div style="font-family: monospace; margin-top: 3rem; padding: 20px">
            Path: {{ route.fullPath }}
        </div>
    </div>
</template>
<script setup>

    const route = useRoute()

</script>