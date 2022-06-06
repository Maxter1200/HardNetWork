<template>
  <center><input class="search_box" placeholder="¿Qué estás buscando?"></center>
</template>

<script>
export default {

}
</script>

<style>

.search_box{
    width: 30%;
    margin: 20px;
    padding: 10px;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    border: 1px solid rgb(15, 30, 160);
    border-radius: 20px;
}

.search_box:focus{
    border: 2px solid rgb(15, 30, 160);
    transition: 0.5s;
}

</style>