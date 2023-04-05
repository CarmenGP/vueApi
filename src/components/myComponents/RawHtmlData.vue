<script>
export default {
    data(){
        return{
            title : "This is My Title",
            person:{
                id: 13,
                name: 'B y Teatro Arriaga Bilbao',
                img : "https://media.istockphoto.com/id/452656947/es/foto/teatro-arriaga.jpg?s=612x612&w=0&k=20&c=kxOPWZj6izl4BORNdLmbJBdgvOnA7r35dESWH2f21TI="
            },
            msg: "B ha tocado es más de una ocasión en este gran teatro",
        }
    },
};
</script>

<template>
        <h3>{{ title }}</h3>
        <div :id="person.id">
            <h4>{{ person.name  }}</h4>
            <img :src="person.img" :alt="person.name">
        </div>
        <h5>{{ msg }}</h5>
</template>

<style lan="css" scoped>
<h3{
    color: magenta;
}
</style>