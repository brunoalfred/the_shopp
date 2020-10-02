<template>
<footer>
    <section class="callout">
        <h2>
            "The Shopp is a place for all your needs, get to enjoy the quality."
        </h2>
        <p>Shoo Visual</p>
    </section>
    <app-footer-links />
    <div class="sarahstuff">
        <p>
            This website is made with love by
            <a href="https://github.com/orgs/Jasiri-Inc/">Jasiri </a>, hosted with
            <a href="https://bit.ly/2G29YwK">Netlify</a>, under
            <a href="https://twitter.com/alfredy_bruno">@brunoalfred (twitter)</a> &
            <a href="https://github.com/brunoalfred">@brunoalfred (github)</a>
        </p>
    </div>
</footer>
</template>

<script>
import AppFooterLinks from "~/components/AppFooterLinks.vue";

export default {
    components: {
        AppFooterLinks,
    },
};
</script>

<style lang="scss" scoped>
.callout {
    width: 100%;
    height: 280px;
    background: url("/callout.jpg") center center no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: white;

    h2 {
        padding: 0 30px;
        text-align: center;
    }
}

.sarahstuff {
    background: black;
    width: 100%;
    padding: 10px 30px;
    color: white;
    text-align: center;
}

a,
a:visited,
a:active {
    color: #c4c3ec;
    font-weight: bold;
}
</style>
