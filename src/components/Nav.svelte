<script>
	export let segment;
</script>

<style>
nav {
	text-align: center;
	display: inline-flex;
    flex-direction: column;
    width: 98vw;
    overflow-wrap: break-word;
		margin: 0 auto;
}
	nav > a {
		color: #ededed;
		font-family: 'IBM Plex Mono';
		padding: 20px 0;
    font-size: 20vw;
		line-height: .7;
    text-decoration: none;
    text-transform: uppercase;
	}

	nav > a:hover {
		color: #333;
	}

	nav > .selected {
		color: #333;	
	}
  footer {
		text-align: center;
	}
	footer > a {
		color: #ededed;
		font-family: 'IBM Plex Mono';
    font-size: 6.8vw;
    text-decoration: none;
    text-transform: uppercase;
	}

	footer > a:hover {
		color: #333;
		cursor: pointer;
	}
</style>
<footer>
<a href="https://www.instagram.com/nano4814/" target="_blank" rel="noopener noreferrer">instagram</a>
<a>dossier</a>
<a>contact</a>
</footer>

<nav>

	<a class:selected='{segment === "artworks"}' href='.'>artworks</a>
	<a class:selected='{segment === "about"}' href='about'>projects</a>
	<a rel=prefetch class:selected='{segment === "blog"}' href='blog'>bio&cv--</a>
</nav>



