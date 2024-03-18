<template>
    <div>
        <h1>AG Grid</h1>
        <GridExample />
    </div>
</template>

<script>
import GridExample from './components/GridExample';

export default {
    name: 'App',
    compatConfig: {
        MODE: 3,
    },
    components: {
        GridExample,
    },
};
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
