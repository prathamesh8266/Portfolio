<script>
    import BodyHelperComp from "./Utils/BodyHelperComp.svelte"
    import {link} from "svelte-spa-router"
    // import arcImg from "../../public/Images/archetecia.jpg"
</script>

<p class="p1">LATEST WORK</p>
<BodyHelperComp 
    description={"Full website design and build for a concept team collaboration platform. This website also includes a beautiful blog. I have built the website and the blog in Webflow which has one of the best CMS for blog hosting."}
    websiteName={"Archetecia"}
    answer={["web design","vanila js"]}
    image={"https://i.postimg.cc/wTjr2TXL/archetecia-Mac.png'"}
    link={"https://archetecis-react-js.pages.dev/"}
/>
<BodyHelperComp 
    description={"Full website design and build for a concept team collaboration platform. This website also includes a beautiful blog. I have built the website and the blog in Webflow which has one of the best CMS for blog hosting."}
    websiteName={"Dwellingo"}
    answer={["web design","vanila js"]}
    image={"https://i.postimg.cc/KzNbWG0L/dwellingo-Mac.png"}
    link={"https://www.dwellingo.in/"}
/>
<BodyHelperComp 
    description={"Full website design and build for a concept team collaboration platform. This website also includes a beautiful blog. I have built the website and the blog in Webflow which has one of the best CMS for blog hosting."}
    websiteName={"Cosy Basket"}
    answer={["web design","vanila js"]}
    image={"https://i.postimg.cc/dV5wntSy/cosyMac.png"}
    link={"https://cosy-basket-e-com.pages.dev/"}
/>
<BodyHelperComp 
    description={"Full website design and build for a concept team collaboration platform. This website also includes a beautiful blog. I have built the website and the blog in Webflow which has one of the best CMS for blog hosting."}
    websiteName={"Covid tracker"}
    answer={["web design","vanila js"]}
    image={"https://i.postimg.cc/g2gLRpVM/covid-Tracker-Mac.png"}
    link={"https://covid-tracker-react-js.pages.dev/"}
/>
<BodyHelperComp 
    description={"Full website design and build for a concept team collaboration platform. This website also includes a beautiful blog. I have built the website and the blog in Webflow which has one of the best CMS for blog hosting."}
    websiteName={"Amazon clone"}
    answer={["web design","vanila js"]}
    image={"https://i.postimg.cc/Zq0HvVdd/amazon-Mac.png"}
    link={"https://master.amazon-clone-react-js.pages.dev/"}
/>

<style>
    .p1{
        margin-top: 30px;
        text-align: center;
        padding-left: 50px;
        font-size: 20px;
        font-weight: 600;
        letter-spacing: 1px;
        color: rgb(201, 201, 201);
    }
    @media screen and (max-width:1080px){
        .p1{
            padding: 0;
            margin-bottom: 30px;
        }
    }
</style>