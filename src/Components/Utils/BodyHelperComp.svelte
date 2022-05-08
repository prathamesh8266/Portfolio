<script>
    import Button from "./Button.svelte"
    import Card from "./Card.svelte"
    export let websiteName;
    export let description;
    export let image;
    export let link;
</script>

<div class="mainHolder">
    <div class="left">
        <p class="p1">LATEST WORK</p>
        <h1>{websiteName}</h1>
        <div class="card">
            <Card answer={"Web design"}/>
        </div>
        <p class="p2">{description}</p>
        <Button class="btn" linkAdd={link}/>
    </div>
    <div class="right">
        <img src={image} class="img"/>
    </div>
</div>


<style>
    .mainHolder{
        display: flex;
        align-items: center;
        justify-content:center;
        flex:1;
    }
    .left{
        padding: 50px;
        padding-right: 150px;
        flex-direction:column;
        display: flex;
        align-items: space-around;
    }
    .p1{
        font-weight: 600;
        letter-spacing: 1px;
        color: rgb(201, 201, 201);
    }
    .left .p1,.p2{
        margin: 10px 0;
        font-family: 'montserrat';
    }
    h1{
        font-size: 50px;
        margin: 20px 0;
    }
    .p2{
        letter-spacing: 0.5px;
    }
    .card{
        margin-top:10px;
        margin-bottom: 25px;
    }
    .right{
        width:100%;
        display:flex;
        align-items: center;
        justify-content: center;
    }
    .img{
        cursor:pointer;
    }
</style>