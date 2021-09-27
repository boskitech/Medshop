<template>
    <div style="width:100%" align="center">
        <v-col>
            <h2>About Us</h2>
            <v-row style="width:70%" justify="space-around"   align="center" >
                <div class="text--primary" data-aos="fade-up" data-aos-delay="150" >
                    <h3>Word of the Day</h3>
                    <p class="text-h4 text--primary">
                        be•nev•o•lent
                    </p>
                    <p>adjective</p>
                    
                        well meaning and kindly.<br>
                        "a benevolent smile"
                </div>
                <div data-aos="fade-left" data-aos-delay="150">
                    <v-card
                        class="mx-auto my-7"
                        max-width="400"
                    >
                        <v-img
                        class="white--text align-end"
                        height="300px"
                        src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                        >
                        <v-card-title>Top 10 Australian beaches</v-card-title>
                        </v-img>

                    </v-card>
                </div>
            </v-row>
        </v-col>
        <v-col>
            <div data-aos="fade-out">
                <v-card class="mx-auto" max-width="100%" align="center" >
                    <v-img class="align-center" align="center" src="../assets/Bg.jpg"  height="400px">
                        <v-card-text>
                            <h2>Hello World </h2>
                            Hello People. Fear Women and Save your life
                        </v-card-text>
                    </v-img>
                </v-card>
            </div>
        </v-col>
        <v-col>
            <v-row style="width:70%" justify="space-around"   align="center" >
                <div data-aos="fade-right" data-aos-delay="150">
                    <v-card
                        class="mx-auto my-7"
                        max-width="400"
                    >
                        <v-img
                        class="white--text align-end"
                        height="200px"
                        src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
                        >
                        <v-card-title>Top 10 Australian beaches</v-card-title>
                        </v-img>

                    </v-card>
                </div>
                <div class="text--primary" data-aos="fade-up" data-aos-delay="150" >
                    <h3>Word of the Day</h3>
                    <p class="text-h4 text--primary">
                        be•nev•o•lent
                    </p>
                    <p>adjective</p>
                    
                        well meaning and kindly.<br>
                        "a benevolent smile"
                </div>
                
            </v-row>
        </v-col>
    </div>
</template>

<script>
    export default {
        name: 'About',
        data(){
            return{

            }
        }
    }
</script>

<style>

</style>