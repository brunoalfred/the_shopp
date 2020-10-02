<template>
<section>
    <ul>
        <li><a href="#">About</a></li>
        <li><a href="#"> Company</a></li>
        <li><a href="#"> Locations</a></li>
        <li><a href="#"> Contact</a></li>
        <li><a href="#"> Hours</a></li>
    </ul>
    <ul>
        <li><a href="#"> Twitter</a></li>
        <li><a href="#"> Facebook</a></li>
        <li><a href="#"> Instagram</a></li>
        <li><a href="#"> LinkedIn</a></li>
    </ul>
    <ul>
        <h4>Newsletter:</h4>
        <input type="text" />
    </ul>
</section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
section {
    width: 80%;
    margin-left: 10%;
    padding: 40px 0;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}

ul {
    list-style: none;
    padding-left: 0;
}

input {
    width: 100%;
}

@media screen and (min-width: 850px) {
    section {
        padding: 40px !important;
    }
}
</style>
