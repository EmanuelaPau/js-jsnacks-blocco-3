<template lang="">
    <div>
        <ul>
            <AppHeaderLink v-for="liElement in liList"
            :navname = liElement.name
            :link = liElement.link />
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

<style lang="scss"></style> 