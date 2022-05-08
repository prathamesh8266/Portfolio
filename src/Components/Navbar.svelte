<script>
    import {link} from "svelte-spa-router"
</script>

<div class="navbar">
    <p>Hatkar.</p>
    <div class="elements">
        <div class="highlight">
            <a use:link href="/personal" class="h2">about me</a>
        </div>
        <div class="highlight">
            <a class="h2">my work</a>
        </div>
        <div class="highlight">
            <a class="h2">get in touch</a>
        </div>
    </div>
</div>

<style>
    a{
        text-decoration: none;
        color: black;
        font-size: 20px;
        font-weight: 500;
    }
    .navbar{
        padding: 40px 60px;
        font-family: 'Muli',sans-serif;
        height: 100px;
        background-color: #f9efe7;
        display:flex;
        justify-content: space-between;
    }
    .navbar p{
        font-size: 22px;
        font-weight: 800;
        letter-spacing: .5px;
    }
    .elements{
        width: 400px;
        display: flex;
        justify-content: space-between;
        cursor: pointer;
    }
    .highlight p{
        font-weight: 200;
		color:black;
    }
    .highlight{
        position: relative;
        height: 100%;
    }
    .highlight .h2{
        position: absolute;
        width: max-content;
        right:0px;
        z-index: 10;
    }
    .h2::after{
        position: absolute;
        bottom: -2px;
        left:0px;
        content: "";
        height: 9px;
        width: 100%;
        background-color:#ffe872;
        z-index: -1;
        transition:all 0.3s
    }
    .highlight:hover > .h2::after{
        height: 25px;
    }
</style>