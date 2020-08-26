
<script>import CharityList from "./CharityList.svelte";

  let title = "Charity";
  setTimeout(function () {
	  title = " Donation";
  }, 2000);
</script>
<div>
	<h1>{title}</h1>
	<CharityList />	
</div>


<style>
	h1 {
		size: 3em;
		color: red;
	}
	div {
		border: 0.5em solid #121212
	}
</style>