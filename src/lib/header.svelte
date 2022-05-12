<script lang="ts">
    import logo from './../assets/logo.svg';
</script>


<div class="header">
    <div class="header-content">
        <a href="/#"><img src={logo} alt="logo"/></a>
        <a href="/#" class="bold">Live</a>
        <a href="/#" class="bold">Push</a>
        <a href="/#" class="bold">Link</a>
        <a href="/#" class="bold">Shop</a>
        <a href="/#" class="bold">Packs</a>
        <a href="/#" class="bold">Help</a>
        <a href="/#" class="bold">More +</a>
    </div>
    
    <div class="header-content">
        <a href="/#" class="bold blue">Try Live for free</a>
        <a href="/#">Account</a>
        <a href="/#">Log out</a>
    </div>
</div>


<style>
    .header {
        background-color: white;
        width: 100%;
        display: flex;
        flex: auto;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        border-bottom: solid 1px rgb(211, 211, 211);
        margin-bottom: 5px;
    }

    .header-content {
        display: flex;
        padding: 10px;
        justify-content: center;
        align-items: center;
    }

    a {
        padding: 0 10px 0 10px;
        text-decoration: none;
        color: black;
    }

    .blue {
        color: blue;
    }
</style>
