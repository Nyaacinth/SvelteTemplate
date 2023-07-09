<script lang="ts">
    import Router from "svelte-spa-router"
    import Splash from "./views/Splash.svelte"

    import "material-icons/iconfont/material-icons.css"
    import "svelte-material-ui/themes/material.css"

    import "@unocss/reset/tailwind-compat.css"
    import "uno.css"

    const routes = {
        "/": Splash
    }
</script>

<Router {routes} />
