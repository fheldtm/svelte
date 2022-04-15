<script>
	import { count } from './store'
	let name = 'kim';
</script>

<main>
	<h1>Hello { $count }!</h1>
	<button on:click={() => { $count += 1 }}>변경</button>
</main>