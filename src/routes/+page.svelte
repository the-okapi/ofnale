<script lang="ts">
    import NavBar from '$lib/NavBar.svelte';
    import ofnale from '$lib/images/ofnale.png';
</script>
<title>Ofnale</title>

<NavBar />

<p>Pour apprendre plus à propos d'Ofnale, visite un des autres catégories sur ce site web.</p>

<img src={ofnale} alt="nature pic" />
<style>
    img {
        width: 39%;
    }
</style>