<script lang="ts">
    import ReliefNavBar from '$lib/ReliefNavBar.svelte';
    import ofnale_map from '$lib/images/ofnale_map.png';
    import ofnale_region from '$lib/images/ofnale_region.png';
</script>
<title>Carte</title>

<ReliefNavBar />

<h1>Carte</h1>

<img src={ofnale_map} class="map" alt="map of olande with ofnale highlighted">

<p>Dans cette carte, Ofnale est sur le bas droit. Les bordures sont rose pour Ofnale seulement.</p>

<img src={ofnale_region} class="region" alt="map of the region of ofnale">

<p>Voici une autre carte, d'Ofnale seulement. Sur la carte, nous avons trois provinces : Ozueli, Outger et Opol. Une des villes dans chaque province est la capitale d'une province. Otnew pour Ozueli, Opurdy pour Outger et Ouagil pour Opol.</p>

<style>
    .map {
        width: 30%;
    }

    .region {
        width: 20%;
    }
</style>