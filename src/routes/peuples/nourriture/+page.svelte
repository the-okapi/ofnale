<script lang="ts">
    import PeuplesSectionNavBar from '$lib/PeuplesSectionNavBar.svelte';
    import crops from '$lib/images/crops.png';
</script>
<title>Nourriture</title>

<PeuplesSectionNavBar />

<h1>Nourriture</h1>

<p>	Dans Ofnale, beaucoup de nourriture est fait des légumes, fruits et fromage. Normalement dans Ofnale, tu cultives les légumes et fruits que tu manges. C’est le même avec le fromage, tu fais le fromage que tu manges.</p>

<img src={crops} alt="crops" />

<style>
    img {
        width: 35%;
    }
</style>