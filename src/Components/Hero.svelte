<script>
    import Button from "./Utils/Button.svelte"
</script>

<div class="main">
    <h1>
        Hi, I'm Prathamesh Hatkar,<br/> 
        <div class="span">
            <div class='spanColor'/>
            <div class='text'>Web Designer</div>
        </div> and <br/> 
        <div class="highlight">
            <div class="h2">Web Developer</div>
        </div>
    </h1>
    <p>
        I design and build beautiful websites for businesses around the globe. If you need a modern and powerful website, send me an email. If we are a good fit, I will give you a time and cost estimate.
    </p>
    <Button link={"/"}/>
    <div class="scrollLabel">SCROLL</div>
</div>

<style>
    .span{
        position:relative;
        display: inline-block;
        height: 61px;
        width: 317px;
        margin-bottom: -12px;
    }
    .span .text {
        z-index: 10;
        position: absolute;
        width: max-content;
    }
    .spanColor{
        position: absolute;
        bottom: 0;
        z-index: 0;
        width: 103%;
        height: 40%;
        background-color: #ffe872;
        transition: all 0.25s linear;
    }
    .span:hover .spanColor {
        height: 100%;
    }
    .main{
        margin: 0;
        font-family: 'Abril Fatface';
        background-color:#f9efe7;
        padding-bottom: 30px;
        margin-bottom: 70px;
    }
   h1{
        font-size: 53px;
        color:black;
        margin-left: 60px;
        padding-top: 60px;
    }
    p{
        max-width: 600px;
        font-size: 20px;
        margin-top: 80px;
        margin-left: 60px;
        letter-spacing: .5px;
        font-family: 'montserrat';
    }
    .scrollLabel{
        font-family:'montserrat';
        letter-spacing: 2px;
        font-weight:500;
        position:absolute;
        bottom:70px;
        right: 60px;
        transform:rotate(90deg)
    }
    .scrollLabel::after{
        position:absolute;
        top:40px;
        left:0px;
        content: "";
        height: 2px;
        width:100px;
        background-color: black;
        animation:myMove 3s infinite;
    }
    @keyframes myMove{
        from{width:0}
        to{width:100px}
    }
    .highlight{
        margin-top: 10px;
        position: relative;
        height: 30px;
        margin-bottom: 50px;
    }
    .highlight .h2{
        position: absolute;
        z-index: 10;
    }
    .h2::after{
        position: absolute;
        bottom: 0px;
        left:0px;
        content: "";
        height: 25px;
        width: 100%;
        background-color:#ffe872;
        z-index: -1;
        transition:all 0.3s
    }
    .highlight:hover > .h2::after{
        height: 60px;
    }
</style>