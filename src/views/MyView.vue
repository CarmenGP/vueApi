<script>
import DirectiveVShow from '../components/myComponents/directives/DirectiveVShow.vue';
import DirectiveVIf from '../components/myComponents/directives/DirectiveVIf.vue';
import RawHtmlData from '../components/myComponents/RawHtmlData.vue';
import SingleComponent from '../components/myComponents/SingleComponent.vue';
import DirectiveVModel from '../components/myComponents/DirectiveVModel.vue';
import DirectiveVFor from '../components/myComponents/DirectiveVFor.vue';
import ComputedProps from '../components/myComponents/computed-properties/ComputedProps.vue';
import ParentComponent from '../components/props/ParentComponent.vue';
export default {
  components: { SingleComponent, RawHtmlData, DirectiveVShow,DirectiveVIf, DirectiveVModel, DirectiveVFor, ComputedProps, ParentComponent }};
</script>

<template>
    <div>
        <h1>My Single Page from FemCoder</h1>
        <h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</h3>
        --------------------------------------------------------------------------------------------
        <SingleComponent /> 
        <SingleComponent></SingleComponent> <!-- (se puede escribir de las dos formas imprime lo mismo en consola) -->
        --------------------------------------------------------------------------------------------
        <RawHtmlData /> 
        --------------------------------------------------------------------------------------------
        <DirectiveVShow />
        --------------------------------------------------------------------------------------------
        <DirectiveVIf />
        <directive-v-model></directive-v-model>

        <directive-v-for></directive-v-for>

        <computed-props></computed-props>

        <parent-component></parent-component>

    </div>
</template>

<style lang="css" scoped>
h1{
    color: red;
}
</style>
