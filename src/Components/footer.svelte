<script>
    import {link} from "svelte-spa-router"
</script>

<div class="footer">
    <p>Designed and developed by <br> Prathamesh Hatkar ©️ 2022</p>
    <div class="links">
        <a>EMAIL</a>
        <a use:link href="https://twitter.com/PrathameshHatk2">TWITTER</a>
        <a>INSTAGRAM</a>
        <a use:link href="https://github.com/prathamesh8266">GITHUB</a>
        <a use:link href="https://www.linkedin.com/in/prathamesh-hatkar-b17aa8193/">LINKEDIN</a>
    </div>
</div>

<style>
    .footer{
        background-color: #f9efe7;
        padding: 50px 20px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .links a{
        color: black;
        text-decoration:none;
        margin: 0 30px;
        font-family: 'montserrat';
        font-weight: 500;
        cursor:pointer;  
    }
    a:hover{
        color: rebeccapurple;
    }
</style>