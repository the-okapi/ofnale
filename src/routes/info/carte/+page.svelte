<script lang="ts">
    import NavBar from '$lib/NavBar.svelte';
    import ofnale_map from '$lib/images/ofnale_map.png';
    import ofnale_region from '$lib/images/ofnale_region.png';
</script>
<title>Carte</title>

<NavBar />

<h1>Carte</h1>

<img src={ofnale_map} class="map" alt="map of olande with ofnale highlighted">

<p>Dans cette carte, Ofnale et sur le bas droit. Les bordures sont rose pour Ofnale seulement.</p>

<img src={ofnale_region} class="region" alt="map of the region of ofnale">

<p>Voici un autre carte, d'Ofnale seulement. Il y a nos trois provinces : Ozueli, Outger et Opol. Tous les villes sauf qu'Oilstour sont le capital d'un province. Otnew pour Ozueli, Opurdy pour Outger et Ouagil pour Opol.</p>

<style>
    .map {
        width: 30%;
    }

    .region {
        width: 20%;
    }
</style>