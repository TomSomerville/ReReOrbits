<script>
	import { draggable } from '@neodrag/svelte';
	import Czone from './Czone.svelte';
</script>
<style>
.banner {
		width:600px;
		height:100px;
		display: inline-block;
		background-image: url(https://i.imgur.com/Qk77nuu.png);
		background-size: 600px 175px;
		background-position: center;
	}
	.re-orbit_logo {
		width:330px;
		height:100px;
		display: inline-block;
		background-image: url(https://i.imgur.com/QgTETB0.png);
		background-size: 330px;		
	}
	.top_bar {
		display: inline-block;
		white-space: nowrap;
		padding: 5px 5px 5px 5px;
		position: center;
		margin-bottom: 5px;
		
	}
</style>

<div class="top_bar">
	<span>
	<div class="re-orbit_logo"></div>
	<div class="banner"></div>
</span>
</div>

<Czone />