<!-- pages/index.vue -->
<template>
    <section style="font-family: sans-serif; padding: 16px;">
        <header>
            <h1>Welcome to the Nuxt Routing Overview</h1>
            <p>
                This page demonstrates how Nuxt handles routing under the <code>pages</code> directory.
            </p>
        </header>

        <article>
            <h2>1. Static Routes</h2>
            <p>
                Any <strong>.vue</strong> file placed directly under <code>pages</code> becomes a route.
                For example, <code>about.vue</code> corresponds to the <code>/about</code> path.
                Click the link below to see a static page example:
            </p>
            <nuxt-link to="/about" style="color:blue; text-decoration:underline;">
                Go to /about
            </nuxt-link>
        </article>

        <article style="margin-top: 24px;">
            <h2>2. Dynamic Routes</h2>
            <p>
                In the <code>pages/blog/[slug].vue</code> file,
                the <code>[slug]</code> indicates a dynamic parameter.
                Thus, Nuxt automatically creates routes like <code>/blog/hello-world</code>,
                <code>/blog/another-post</code>, etc. The text in place of
                <code>[slug]</code> becomes <code>$route.params.slug</code> in the component.
            </p>
            <p>
                Try navigating to a dynamic route:
            </p>
            <nuxt-link to="/blog/my-first-post" style="color:blue; text-decoration:underline;">
                Go to /blog/my-first-post
            </nuxt-link>
        </article>

        <article style="margin-top: 24px;">
            <h2>3. Catch-all Routes</h2>
            <p>
                A file named <code>[...catchall].vue</code> captures <em>any</em> path segments
                not otherwise matched by existing routes. For example, <code>/random</code>,
                <code>/some/madeup/path</code>, or <code>/blog/extra/paths</code>.
                The value can be accessed via <code>$route.params.catchall</code> as an array or string.
            </p>
            <p>
                Try navigating to a random path:
            </p>
            <nuxt-link to="/random/unmatched" style="color:blue; text-decoration:underline;">
                Go to /random/unmatched
            </nuxt-link>
        </article>

        <hr style="margin: 24px 0;" />

        <footer>
            <p>
                Current URL Path: <strong>{{ route.path }}</strong>
            </p>
            <p>
                Use <code>useRoute()</code> from <code>vue-router</code> to inspect route data
                anywhere in your components.
            </p>
            
        </footer>
    </section>
</template>

<script setup>
    
    const route = useRoute()
</script>
