<template>
    <div id="app">
        <div class="layout">
            <div class="nav">
                <div>
                    <span>Greef Company</span>
                </div>
                <div class="containerList">
                    <ul>
                        <li>INÍCIO</li>
                        <li>SOBRE NÓS</li>
                        <li>CONTATO</li>
                    </ul>
                </div>
            </div>

            <slot></slot>

        </div>
        <div>
            <h1>FOOTER</h1>
        </div>
    </div>
</template>

<style scoped>

.layout {
    background-color: #F1F5EB;
}

.nav {
    display: flex;
    padding: 40px 59px;
    justify-content: space-between;
}

span {
    color: #034833;
    font-size: 32px;
    font-weight: 700;
    cursor: pointer;
}

ul {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    list-style-type: none;
}

li {
    margin-right: 35px;
    color: #034833;
    font-size: 15px;
    font-weight: 700;
    cursor: pointer;
}

</style>