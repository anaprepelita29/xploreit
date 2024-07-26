<template>
    <section class="sectiune-container">
        <div class="container1">

            <div class="profil">
                <img src="/imagini/c1.jpg">
                <p>Emma Roberts</p>
            </div>
            <div>
                <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
                <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
                <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
                <img src="/imagini/start.png" style="height: 10px; width: 10px;">
                <img src="/imagini/start.png" style="height: 10px; width: 10px;">
            </div>

            <div>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur dicta exercitationem adipisci
                    iusto, quas sequi, consectetur harum, dolorum sed assumenda nihil repellendus doloribus dolor
                    molestiae maiores incidunt quo. Aspernatur, voluptates!</p>
            </div>

        </div>
        <div class="container1">

<div class="profil">
    <img src="/imagini/c1.jpg">
    <p>Emma Roberts</p>
</div>
<div>
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
</div>

<div>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur dicta exercitationem adipisci
        iusto, quas sequi, consectetur harum, dolorum sed assumenda nihil repellendus doloribus dolor
        molestiae maiores incidunt quo. Aspernatur, voluptates!</p>
</div>

</div>
<div class="container1">

<div class="profil">
    <img src="/imagini/c1.jpg">
    <p>Emma Roberts</p>
</div>
<div>
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
</div>

<div>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur dicta exercitationem adipisci
        iusto, quas sequi, consectetur harum, dolorum sed assumenda nihil repellendus doloribus dolor
        molestiae maiores incidunt quo. Aspernatur, voluptates!</p>
</div>

</div>
<div class="container1">

<div class="profil">
    <img src="/imagini/c1.jpg">
    <p>Emma Roberts</p>
</div>
<div>
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
</div>

<div>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur dicta exercitationem adipisci
        iusto, quas sequi, consectetur harum, dolorum sed assumenda nihil repellendus doloribus dolor
        molestiae maiores incidunt quo. Aspernatur, voluptates!</p>
</div>

</div>
<div class="container1">

<div class="profil">
    <img src="/imagini/c1.jpg">
    <p>Emma Roberts</p>
</div>
<div>
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
</div>

<div>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur dicta exercitationem adipisci
        iusto, quas sequi, consectetur harum, dolorum sed assumenda nihil repellendus doloribus dolor
        molestiae maiores incidunt quo. Aspernatur, voluptates!</p>
</div>

</div>
<div class="container1">

<div class="profil">
    <img src="/imagini/c1.jpg">
    <p>Emma Roberts</p>
</div>
<div>
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/star1.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
    <img src="/imagini/start.png" style="height: 10px; width: 10px;">
</div>

<div>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consequatur dicta exercitationem adipisci
        iusto, quas sequi, consectetur harum, dolorum sed assumenda nihil repellendus doloribus dolor
        molestiae maiores incidunt quo. Aspernatur, voluptates!</p>
</div>

</div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.sectiune-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 20px;
    grid-row-gap: 20px;
    margin-bottom: 50px;
}

.container {
    background-color: rgba(217, 232, 227, 0.486);
}

.container1 {
    background-color: #ffffff;
    border: 2px solid #cccccc;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    max-width: 300px;
    text-align: center;


}

.profil>img {
    height: 50px;
    width: 50px;
    border-radius: 100%;
    margin-left: 10px;
    margin-top: 10px;
}

.profil>p {
    flex-direction: row;
    text-align: center;
    align-content: center;
    font-size: 18px;

}

</style>