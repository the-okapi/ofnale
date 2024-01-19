<script lang="ts">
    import NavBar from '$lib/NavBar.svelte';
    import ofnale_map from '$lib/ofnale_map.png';
</script>
<title>Géographie</title>

<NavBar />

<h1>Géographie</h1>

<img src={ofnale_map} alt="map of olande with ofnale highlighted">

<p>Dans cette carte, Ofnale et sur le bas droit. Les bordures sont rose pour Ofnale seulement. Ils sont rose pour être plus facile à trouver.</p>

<style>
    img {
        width: 41%;
    }
</style>