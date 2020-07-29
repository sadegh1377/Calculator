<template>
    <div class="home container">
        <calculator/>
    </div>
</template>

<script>
    import Calculator from "../components/Calculator";

    export default {
        name: 'Home',
        components: {
            Calculator,
        }
    }
</script>
