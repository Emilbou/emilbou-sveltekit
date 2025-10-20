<script lang="ts">
    import type { PageProps } from './$types';

    let {data}: PageProps = $props();
</script>

<div>
    <h1>bonjour</h1>
    <p>{data.title}</p>
    <p>{data.content}</p>
    <p>{data.slug}</p>
</div>