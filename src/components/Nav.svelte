<script>
	export let segment;
</script>

<style>
nav {
	position: absolute;
	top: 30px;
}
	a {
		padding: 20px;
	}
</style>

<nav>

	<a class:selected='{segment === undefined}' href='.'>home</a>
	<a class:selected='{segment === "about"}' href='about'>about</a>
	<a rel=prefetch class:selected='{segment === "blog"}' href='blog'>blog</a>

	<!-- <ul>
		<li><a class:selected='{segment === undefined}' href='.'>home</a></li>
		<li><a class:selected='{segment === "about"}' href='about'>about</a></li>

		<li><a rel=prefetch class:selected='{segment === "blog"}' href='blog'>blog</a></li>
	</ul> -->
</nav>


