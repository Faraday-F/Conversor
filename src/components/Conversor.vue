<template>

    <div class="conversor">
        <h2>
            {{moedaA}} Para {{moedaB}}
        </h2>
        <input type="text">
        <button>Converter</button>


    </div>
    
</template>


<script>
export default {
    name: "conversor",
    props: ["moedaA","moedaB"]

    
};

</script>


<style scoped>

</style>
