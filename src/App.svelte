<<<<<<< HEAD
<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>
=======

<script>import CharityList from "./CharityList.svelte";
>>>>>>> 9b75be86162dacae2511adbd51d09ab958897c50

  let title = "Charity";
  setTimeout(function () {
	  title = " Donation";
  }, 2000);
</script>

<h1>{title}</h1>
<CharityList />

<style>
	h1 {
		size: 3em;
		color: red;
	}
</style>