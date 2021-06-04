<script>

</script>

<nav>
    <div class="navbar_logo">
        <img src="./auth-decoder-logo.svg" alt="Auth Decoder Logo">
    </div>
    <div class="navbar_menu">
        <a href="#1">OAuth2</a>
        <a href="#2">OpenID Connect</a>
        <a href="#3">GitHub</a>
    </div>
</nav>

<style>
    nav {
        display: flex;
        align-items: center;
        flex-basis: 80%;
        border-bottom: 1px solid #aeaeae;
    }

    .navbar_logo {
        flex-grow: 1;
        justify-content: flex-start;
        padding-left: 4%;

    }

    .navbar_logo img {
        height: 3em;
    }

    .navbar_menu {
        flex-basis: 55%;
        display: flex;
        justify-content: space-around;
    }

    nav a {
        text-decoration: none;
    }

</style>