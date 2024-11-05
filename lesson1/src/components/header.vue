<template>
    <header>
        <div class="container">
            <nav>
                <a href="./App.vue">
                    <img src="../../public/vue.png" alt="png" />
                </a>
                <ul class="list">
                    <li class="list_item">
                        <a href="#" class="list_item-link">Home</a>
                    </li>
                    <li class="list_item">
                        <a href="#" class="list_item-link">About</a>
                    </li>
                    <li class="list_item">
                        <a href="#" class="list_item-link">Service</a>
                    </li>
                    <li class="list_item">
                        <a href="#" class="list_item-link">Projects</a>
                    </li>
                    <li class="list_item">
                        <a href="#" class="list_item-link">Contact</a>
                    </li>
                    <li class="list_item">
                        <a href="#" class="list_item-link">FAQ</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    background-color: #201e43;
    padding: 0 24px;

    nav {
        width: 100%;
        height: 140px;
        display: flex;
        align-items: center;
        justify-content: space-between;

        img {
            width: 60px;
            height: auto;
        }

        ul {
            width: 80%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            list-style: none;

            a {
                color: rgb(204, 232, 255);
                text-decoration: none;
                text-transform: capitalize;

                &:hover {
                    color: rgb(255, 255, 255);
                }
            }
        }
    }
}
</style>
