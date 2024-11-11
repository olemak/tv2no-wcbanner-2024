<script lang="ts">
    let { current } = $props<{current:string}>();
</script>

<section class="banner">
    <h2>This is the banner</h2>
    <h3>Change the markup</h3>
    <p>Thingnes Bø: {current}</p>
    <p>Bjørndalen: 95</p>
</section>

<style>

    .banner {
        width: 100%;
        border: 2px solid #000;
        padding: 1rem;
        background: blue;
        color: white;
        display: flex;
        max-width: 768px;
        justify-content: space-between;
        align-items: center;
        margin: 5rem auto;
    }
</style>