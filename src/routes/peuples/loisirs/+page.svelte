<script lang="ts">
    import PeuplesSectionNavBar from '$lib/PeuplesSectionNavBar.svelte';
    import nature from '$lib/images/nature.png';
</script>
<title>Loisirs</title>

<PeuplesSectionNavBar />

<h1>Loisirs</h1>

<p>	Dans Ofnale, il y a beaucoup de loisirs communs. Mais, il y a un loisir qui est le plus commun. Ce loisir est la nature. Ofnale à une forêt et une montagne qui sont très beaux, donc les promenades sont populaires. Cette nature est très proche aux villes.</p>

<img src={nature} alt="nature" />

<style>
    img {
        width: 35%;
    }
</style>