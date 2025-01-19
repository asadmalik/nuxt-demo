<template>
    <div>
        <h2>Catch-all Page</h2>
        <p>You landed on: {{ route.params.catchall }}</p>

        <div style="padding: 20px; margin:20px; background-color: #eee;">
            <p>
                That’s the basic idea for routing in Nuxt 3:
            </p>
            <ul>
                <li>Static routes: pages/somePage.vue → /somePage </li>
                <li>Dynamic routes: pages/folder/[param].vue → /folder/:param</li>
                <li>Catch-all: pages/[...everything].vue → capture all unmatched routes</li>
            </ul>
        </div>
    </div>
</template>

<script setup>
     const route = useRoute()
</script>