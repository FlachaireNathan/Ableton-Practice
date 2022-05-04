<script lang="ts">
    import logo from './logo.svg';
</script>


<div class="header">
    <div class="header-content">
        <a href="/#"><img src={logo} alt="logo"/></a>
        <a href="/#">Live</a>
        <a href="/#">Push</a>
        <a href="/#">Link</a>
        <a href="/#">Shop</a>
        <a href="/#">Packs</a>
        <a href="/#">Help</a>
        <a href="/#">More +</a>
    </div>
    
    <div class="header-content">
        <a href="/#">Try Live for free</a>
        <a href="/#">Account</a>
        <a href="/#">Log out</a>
    </div>
</div>


<style>
    .header {
        display: flex;
        flex: auto;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }

    .header-content {
        padding: 10px;
        justify-content: center;
        align-items: center;
    }
</style>
