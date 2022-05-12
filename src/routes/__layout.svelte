<script>
import Header from "$lib/header.svelte";
import Subheader from "$lib/subheader.svelte";

</script>


<div class="main">
    <Header></Header>
    <Subheader></Subheader>
    <slot></slot>
</div>


<style global>
body {
    background-color: #F3F3F3;
    font-family: futura-pt,Avenir,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Helvetica,Arial,sans-serif;
}

.bold {
    font-weight: bold;
}

.main {
    margin-left: auto;
    margin-right: auto;
    max-width: 1600px;
}
</style>