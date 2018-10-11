<template>
    <header>
        <img src="../assets/logo.png" alt=""> <h1>Galvanize Reads</h1>
    </header>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style>
header {
    grid-row: 1 / 2;
    display: grid;
    grid-template-columns: 25% 50% 15%;
    grid-template-rows: 50% 50%;
}

header img {
    grid-row: 1/3;
    grid-column: 1/2;
    height: 100px;
    width: auto;
}

header h1 {
    grid-row: 1/3;
    grid-column: 1/2;
    padding: 5px;
}
</style>