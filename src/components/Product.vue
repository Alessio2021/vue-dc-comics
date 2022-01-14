<template>
    <li>
        <div class="container-img">
            <img :src="img" :alt="alt">
        </div>
        <h4>{{ alt }}</h4>
    </li>
</template>

<script>
export default {
    name: "Product",
    props: {
        img: {
            type: String,
        },
        alt: {
            type: String,
        }
    }
}
</script>

<style lang="scss" scoped>
    li {
        list-style-type: none;
        flex-basis: calc((100% / 6) - 0.4em);
        margin: 1em 0;
        .container-img {
            width: 200px;
            height: 200px;
            overflow: hidden;
            img {
                width: 100%;
            }
        }
        h4 {
            color: white;
            margin: 1em 0;
            text-transform: uppercase;
        }
    }
</style>