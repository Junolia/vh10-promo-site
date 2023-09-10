<script>
    import FooterApartment from "../components/footerApartment.svelte";
</script>

<footer>
    <div id="footerApartment">
        <FooterApartment/>
    </div>
    <a href="../components/firstCloud.svelte">Apply Now</a> 
    <div class="links">
        <div class="block">
            <a href="">Jude Portal</a>
            <br>
            <a href="">Asurion</a>
            <br>
            <a href="">Crossyear</a>
        </div>
        <div class="block">
            <a href="">Instagram</a>
            <br>
            <a href="">Youtube</a>
            <br>
            <a href="">Github</a>
        </div>

    </div>
   
</footer>

<style>
    footer {
        width: auto;
        height: 501px;
        background-color: #0E0E1A;
        text-align: left;
        font-size: 24px;
    }
    a {
        color: white;
        text-decoration: none;
        position: absolute;
    }
    .links {
        margin:auto;
    }
    .block {
        width: 511px;
        height: 360px;
        display: inline-block;
        background-color: pink;
    }
</style>