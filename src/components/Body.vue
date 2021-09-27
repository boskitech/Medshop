<template>
  <div width="100%">
    <div class="body" data-aos="fade-in "><Searchbar />
    <Categories /></div>
    <v-divider></v-divider>
    <About />
    <Instyle />
  </div>
</template>

<script>
import Searchbar from './Searchbar';
import Categories from './Categories';
import About from './About';
import Instyle from './Instyle';

export default {
    name: 'Body',
    components:{
        Searchbar,
        Categories,
        About,
        Instyle
    },
    data(){
        Categories
        return{
            
        }
    }
  }
</script>

<style >
.body {
 background-image: url('../assets/Bg3.jpg');
 background-size: cover;
}
</style>