<script lang="ts">
    import { onMount } from 'svelte';

    let domain = "";
    onMount(() => domain = window.location.hostname);
</script>

<svelte:head>
    <title>tuna2134 managed domain</title>
</svelte:head>
<div class="font-mplus1p w-full flex justify-center min-h-screen items-center bg-slate-800 text-white">
    <div class="px-auto space-y-2">
        <h1 class="text-4xl font-bold">tuna2134 managed domain</h1>
        <div class="space-y-2">
            <div>
                <p>{domain} is managed by tuna2134.</p>
                <p>If you need to contact us, please send email.</p>
            </div>
            <p>Email: <a class="text-sky-400" href="mailto:me@tuna2134.dev">me@tuna2134.dev</a></p>
        </div>
    </div>
</div>