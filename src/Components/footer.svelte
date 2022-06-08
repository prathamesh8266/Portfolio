<script>
    import {link} from "svelte-spa-router"
</script>

<div class="footer">
    <p>Designed and developed by <br> Prathamesh Hatkar ©️ 2022</p>
    <div class="links">
        <a use:link href='mailto:hatkar.prathameshd@gmail.com'>EMAIL</a>
        <a use:link href="https://twitter.com/PrathameshHatk2" target='_'>TWITTER</a>
        <a use:link href='https://www.instagram.com/prathamesh_hatkar10/' target='_'>INSTAGRAM</a>
        <a use:link href="https://github.com/prathamesh8266" target='_'>GITHUB</a>
        <a use:link href="https://www.linkedin.com/in/prathamesh-hatkar-b17aa8193/" target='_'>LINKEDIN</a>
    </div>
</div>

<style>
    .footer{
        background-color: #f9efe7;
        /* background-color: black; */
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