<template>
    <div style="width:100%; padding-top:55px" align="center">
        <h2><v-icon style="margin-top:-5px; color:green  ">mdi-medical-bag</v-icon>MedShop</h2>
        <form>
            <v-text-field
            solo
            placeholder="Which Medicine Are You Looking?"
            required
            align="center"
            height="60px"
            style="width:65%; text-align:center;"
            ><v-icon prepend>mdi-medical-bag</v-icon></v-text-field>
        </form> 
    </div>
</template>

<script>
    export default{
        name: 'Searchbar',
    }

</script>


<style>

</style>