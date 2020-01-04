<script>
	export let segment;
</script>

<style>
nav {
	display: inline-flex;
    flex-direction: column;
    max-width: 40vw;
    overflow-wrap: break-word;
}
	a {
		color: #ededed;
		font-family: 'IBM Plex Mono', monospace;
		padding: 20px;
    font-size: 140px;
    text-decoration: none;
    text-transform: uppercase;
    line-height: 96px;
    letter-spacing: -10px;
	}

	a:hover {
		color: black;
	}

	.selected {
		color: black;	
	}
</style>

<nav>

	<a class:selected='{segment === undefined}' href='.'>artworks</a>
	<a class:selected='{segment === "about"}' href='about'>projects&expos</a>
	<a rel=prefetch class:selected='{segment === "blog"}' href='blog'>bio&cv</a>

	<!-- <ul>
		<li><a class:selected='{segment === undefined}' href='.'>home</a></li>
		<li><a class:selected='{segment === "about"}' href='about'>about</a></li>

		<li><a rel=prefetch class:selected='{segment === "blog"}' href='blog'>blog</a></li>
	</ul> -->
</nav>


