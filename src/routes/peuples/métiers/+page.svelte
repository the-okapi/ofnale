<script lang="ts">
    import PeuplesSectionNavBar from '$lib/PeuplesSectionNavBar.svelte';
    import farming from '$lib/images/farming.png';
</script>
<title>Métiers</title>

<PeuplesSectionNavBar />

<h1>Métiers</h1>

<p>	Dans Ofnale, il y a trois types de métiers les plus grands :  cultiver, technologie et gouvernement. On a besoin de personnes qui cultivent, car on n’importe pas la nourriture des autres pays. Les personnes qui travaillent dans la technologie sont vitales parce qu’ils font le travail pour que les ordis fonctionnent dans Ofnale. Le gouvernement est important, car c’est le gouvernement.</p>

<img src={farming} alt="crops" />

<style>
    img {
        width: 35%;
    }
</style>