<template>
    <div class="container">
        <div class="containerInfo">
            <div>
                <p>Do campo Para sua mesa!</p>
            </div>
            <div>
                <AssetsGreef-Company />
            </div>
        </div>
    </div>
</template>

<style scoped>

.container {
    background-image: url('/components/assets/background.svg');
    background-color: #034833;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    width: 100%;
    height: 800px;
    border-radius: 50px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.containerInfo {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100%;
}

p {
    font-size: 80px;
    color: #fff;
    font-weight: 700;
}

</style>