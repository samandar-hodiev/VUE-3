<template>
    <footer>
        <div class="container">
            <div class="container">
                <div>
                    <p>&copy; {{ new Date().getFullYear() }} || VUE 3</p>
                </div>
            </div>
        </div>
    </footer>
</template>


<style lang="scss" scoped>
footer {
    background-color: #134B70;
    width: 100%;
    height: 110px;

    div {
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: center;

        p {
            color: rgb(150, 206, 255);
            transition: all 0.2s ease;

            &:hover {
                color: white;
            }
        }
    }

}
</style>