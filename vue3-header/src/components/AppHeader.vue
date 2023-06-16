<template lang="">
    <div>
        <ul>
            <AppHeaderLink v-for="liElement in nav"
            :navname = liElement.name
            :link = liElement.link 
            />
        </ul>
    </div>
</template>
<!-- <script> -->
<script>
import AppHeaderLink from './AppHeaderLink.vue';

export default {
    components: {
        AppHeaderLink,
    },

    name: 'AppHeader',

    data() {
        return {
            nav: [
                {
                    name: 'gino',
                    link: '#'
                },
                {
                    name: 'ciao',
                    link: '#'
                },
                {
                    name: 'boh',
                    link: '#'
                },
                {
                    name: 'bla',
                    link: '#'
                },
                {
                    name: 'buh',
                    link: '#'
                },
            ]
        }
    },
    methods() {
    },
}		
</script>

<style lang="scss">
ul {
    list-style-type: none;
    display: flex;
    margin: 0 auto;
    margin-top: 50px;
    max-width: 700px;
    justify-content: space-between;

    li {
        a {
            text-decoration: none;
            color: black;
        }
    }
}
</style> 