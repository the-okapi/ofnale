<script lang="ts">
    import NavBar from '$lib/NavBar.svelte';
    import parti_vert from '$lib/images/parti_vert.png';
    import parti_des_peuples from '$lib/images/parti_des_peuples.png';
    import parti_olande from '$lib/images/parti_olande.png';
</script>
<title>Partis Politiques</title>

<NavBar />

<h1>Partis Politiques</h1>

<p>Dans Ofnale, il y a trois partis politiques. Un des qui a le plus des votes, un qui a un peu des votes et un qui n'a rien de votes. Les trois partis sont :</p>
<ul class="partis">
    <li><a class="green" href="/gouvernement/partis/vert"><img src={parti_vert} alt="parti vert"> Parti Vert</a></li>
    <li> <a class="blue" href="/gouvernement/partis/peuples"><img src={parti_des_peuples} alt="parti des peuples"> Parti des Peuples</a></li>
    <li><a class="black" href="/gouvernement/partis/olande"><img src={parti_olande} alt="parti olande"> Parti Olande</a></li>
</ul>

<style>
    img {
        width: 50%;
    }
</style>