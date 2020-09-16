<template>
    <div id="newSponge">
        <img id="jelly" width="200px" src="https://vignette.wikia.nocookie.net/spongebobgalaxy/images/1/11/King_J.jpg/revision/latest/scale-to-width-down/340?cb=20140916203740" alt="jellyFish">
        <div></div>
        <img id="bob" width="90px" src="https://i.redd.it/cxmxo7yol5811.jpg" alt="spongeBob">
    </div>
</template>

<script>
export default {
    name: "new-sponge"
}
</script>

<style scoped>
    #newSponge {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 0.5fr 1fr;
        
    }

    #jelly {
        display: grid;
        justify-self: baseline;
    }

    #bob {
        display: grid;
        align-self: end;
        justify-self: baseline;

    }
</style>