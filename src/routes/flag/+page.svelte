<script lang="ts">
    import NavBar from '$lib/NavBar.svelte';
    import flag_waving from '$lib/flag_waving.png';
    import flag from '$lib/flag.png';
</script>
<title>Drapeau</title>

<NavBar />
<h1>Drapeau</h1>
<img src={flag_waving} alt="the flag of ofnale while waving" />
<p>Le drapeau d'Ofnale est un drapeau simple, mais il a un sens. Dans le drapeau, il y a juste deux couleurs. Chaque carrée signifie quelque chose de différent. La carrée d'or sur le fond signifie le sable sur nos rivages. La carrée bleue sur le fond signifie la mer. La carrée d'or sur le dessus signifie le soleil et la carrée bleue sur le dessus signifie le ciel.</p>
<img src={flag} alt="the flag of ofnale" />

<style>
    img {
        height: 45%;
        width: 15%;
    }
</style>