<template>
    <li>
        <a :href="link"> {{ navname }} </a>
    </li>
</template>

<script>
export default {
    name: 'AppHeadeLink',
    props: {
        navname: String,
        link: String,
    },
    data() {
        return {
        }
    },
    methods() {
    },
}		
</script>
<style scoped lang="scss"></style> 