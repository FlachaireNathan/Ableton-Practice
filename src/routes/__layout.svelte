<script>
import Header from "$lib/header.svelte";
import Subheader from "$lib/subheader.svelte";

</script>


<Header></Header>
<Subheader></Subheader>
<slot></slot>

<style global>
body {
    font-family:Arial, Helvetica, sans-serif
}

.bold {
    font-weight: bold;
}
</style>