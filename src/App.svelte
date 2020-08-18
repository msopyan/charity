
<script>import CharityList from "./CharityList.svelte";

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