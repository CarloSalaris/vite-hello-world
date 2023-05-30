<script>
export default {
    name: "AppHero"
}
</script>

<template>
    <div id="heroContainer">

        <div class="center-block">
            <h2>JUMBOTRON TITLE</h2>
            <p>Jumbotron paragraph. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorum dicta ullam obcaecati
                accusamus eveniet itaque quasi perferendis totam, reprehenderit, blanditiis provident architecto doloribus
                inventore sed, voluptatibus fugiat magnam explicabo! Numquam.</p>
            <button class="big-button"><a href="#"><i class="fa-solid fa-arrow-down-long"></i> BUTTON 1</a></button>
            <button class="big-button black-back"><a href="#">BUTTON 2</a></button>
        </div>

    </div>
</template>

<style scoped>
#heroContainer {
    color: cornsilk;
    padding: 50px;
    border-radius: 20px;
    background-image: url(../assets/ViteVine.webp);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.center-block {
    width: 80%;
    padding: 20px;
    margin: auto;
    background-color: rgba(0, 0, 0, 0.385);
    border-radius: 20px;
}

button {
    margin: 10px;
    background-color: cadetblue;
}

button:hover {
    background-color: rgb(142, 197, 199);
}

button:hover a {
    color: rgb(6, 90, 90);
}

a {
    color: inherit;
    height: 100%;
}
</style>