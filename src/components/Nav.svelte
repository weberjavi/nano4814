<script>
	export let segment;
</script>

<style>
nav {
	text-align: center;
	
}
	nav > a {
		color: #ededed;
		font-family: 'IBM Plex Mono';
    font-size: 6.8vw;
    text-decoration: none;
    text-transform: uppercase;
	}

	nav > a:hover {
		color: #333;
	}

	.selected {
		color: #333;	
	}

	.all {
		padding-left: 2.8vw;
	}
  footer {
		text-align: center;
		line-height: 1;
		margin-top: 10px;
	}
	footer > a {
		color: #ededed;
		font-family: 'IBM Plex Mono';
    font-size: 6.8vw;
    text-decoration: none;
    text-transform: uppercase;
	}
	section {
		display: flex;
		flex-direction: row;
		flex-wrap: wrap;
		width: 94vw;
		margin: 0 auto;
	}
	span {
		color: #ededed;
		font-family: 'IBM Plex Mono';
    font-size: 3.89vw;
    text-decoration: none;
    text-transform: uppercase;
	}

	footer > a:hover,
	span:hover {
		color: #333;
		cursor: pointer;
	}
</style>
<footer>
<a href="https://www.instagram.com/nano4814/" target="_blank" rel="noopener noreferrer">instagram</a>
<a>dossier</a>
<a>contact</a>
<a>artwork</a><a>projects</a><a>drawings</a>
<section>
<span>2020</span><span>2019</span><span>2018</span><span>2017</span><span>2016</span><span>2015</span>
<span>2014</span><span>2013</span><span>2012</span><span>2011</span><span>2010</span><span>2009</span>
<span>2008</span><span>2007</span><span>2006</span><span>2005</span><span>2004</span><span>2002</span>
<span>2001</span><span class="selected all"> ALL</span>
</section>
</footer>


