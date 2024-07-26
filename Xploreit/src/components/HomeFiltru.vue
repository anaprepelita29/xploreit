<template>
    <section>
        <div class="filtru">
            <ul class="lista-filtru">
                <li><img src="/imagini/filter.png" imagine-filtru class="imagine-filtru"></li>
                <li class="cuv-filters">Filters</li>
            </ul>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.filtru {
    align-content: flex-end;
    background-color: rgba(255, 255, 255, 0.227);
    margin-right: 10px;


}

.lista-filtru {
    list-style: none;
    display: flex;
    flex-direction: row-reverse;
}

.imagine-filtru {
    display: flex;
    flex-direction: row;
    align-items: flex-end;
    align-items: center;
    width: 30px;
    height: 30px;
    margin-right: 30px;

}

.cuv-filters {
    font-size: 25px;
    align-content: center;
}

</style>