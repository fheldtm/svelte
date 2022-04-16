<script>
  import Child from './Child.svelte'

  export let name
</script>

<h2>Parent</h2>
<Child {name} />