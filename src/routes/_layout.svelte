<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<style>
h1 {
	text-align: center;
	margin: 0;
	font-family: 'IBM Plex Mono';
	padding-top: 20px;
  font-size: 20vw;
	line-height: .7;
}
</style>

<h1>NANO4814</h1>
<Nav {segment}/>

<slot></slot>