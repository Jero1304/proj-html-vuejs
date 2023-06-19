<template>
        <ul>
            <li class="r"></li>
            <li class="l"></li>
            <li class="r"></li>
            <li class="l"></li>
            <li class="r"></li>
            <li class="l"></li>
            <li class="r"></li>
            <li class="l"></li>
            <li class="r"></li>
            <li class="l"></li>
        </ul>
</template>

<script>
export default {
    name: 'name'

}
</script>

<style scoped>
ul,
li {
    list-style: none;
    padding: 0;
}

ul {
    display: flex;
    width: 500px;
    padding: 1% 0;

}

li {
    background-color: rgb(255, 255, 2);
    height: 30px;
    width: 2px;
    margin: 0 5px;
}

.r {
    rotate: 25deg
}

.l {
    rotate: 155deg
}
</style>