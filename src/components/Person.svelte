<script>
    export let name = 'Udefined name';
    let age =  'Udefined age'
    let job =  'Udefined job'
</script>

<div>
    <p>Имя: <strong>{name}</strong></p>
    <p>Занятие: <strong>{job}</strong></p>

    {#if age < 18}
    <p>Пиво продавать нельзя</p>
    {:else}
    <p>Делай что хочешь</p>
    {/if}
</div>

<!-- Styles -->
<style>
    div {
        border: 1px solid black;
        padding: 1rem;
        margin-bottom: 1rem;
    }
</style>