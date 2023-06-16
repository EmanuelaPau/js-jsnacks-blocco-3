<template lang="">
    <div>
        <AppHeaderLink/>
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
                'gino',
                'ciao',
                'boh',
                'bu',
            ]
        }
    },
    methods() {
    },
}		
</script>

<style lang="scss"></style> 