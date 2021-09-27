<template>
<div style="height:65px">
    <v-card
    class="mx-auto overflow-hidden" style="border-radius:0" width="100%" light >
    <v-app-bar color="green" height="70px" short app >

      <v-toolbar-title text color="text--white lighten-5" style="color:white">
          <v-icon style="margin-top:-5px; color:white" white>mdi-medical-bag</v-icon>MedShop
      </v-toolbar-title>
      <v-spacer></v-spacer>
     <!-- <v-btn text color="white lighten-5" style="margin-right:5px color:white">
        About <v-icon>mdi-comment-text</v-icon>
      </v-btn>-->
      
      <!-- cart menu ----->
      <v-menu  bottom  offset-y width="300px" >
        <template v-slot:activator="{ on, attrs }">
          <v-btn text color="white lighten-5" v-bind="attrs" v-on="on"  >
            <v-icon>mdi-cart</v-icon>
          </v-btn>
        </template>
        <v-card width="350px" height="300" style="overflow: auto">
          <div class="cart-items">
            <v-list-item three-line>
              <v-list-item-content>
                <div class="text-overline">
                  <v-list-item-title class="text-h7">
                    Tetracyclene
                  </v-list-item-title>
                </div>
                <v-list-item-subtitle>For symptoms relating to stomach ache</v-list-item-subtitle>
              </v-list-item-content>

                
              <v-list-item-avatar tile size="80" color="grey"  >
                <v-img  style="padding:0;" src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"></v-img>
              </v-list-item-avatar>
            </v-list-item>
            <v-card-actions> 
              <v-chip class="ma-2" color="green" text-color="white" align="right">
                2 pcs
              </v-chip>
              <v-btn outlined rounded text color="green">
                Buy Now
              </v-btn>
            </v-card-actions>
          </div><v-divider></v-divider>

          <div class="cart-items">
            <v-list-item three-line>
              <v-list-item-content>
                <div class="text-overline">
                  <v-list-item-title class="text-h7">
                    Panadol
                  </v-list-item-title>
                </div>
                <v-list-item-subtitle>For symptoms relating to stomach ache</v-list-item-subtitle>
              </v-list-item-content>

                
              <v-list-item-avatar tile size="80" color="grey"  >
                <v-img  style="padding:0;" src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"></v-img>
              </v-list-item-avatar>
            </v-list-item>
            <v-card-actions> 
              <v-chip class="ma-2" color="green" text-color="white" align="right">
                2 pcs
              </v-chip>
              <v-btn outlined rounded text color="green" >
                Buy Now
              </v-btn>
            </v-card-actions>
          </div>
        </v-card>
      </v-menu>
      <!-- Account menu ----->
      
       <v-menu
        bottom
        offset-y
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn text color="white lighten-5"
            v-bind="attrs"
            v-on="on"
          >
            <v-icon>mdi-account-circle</v-icon>
          </v-btn>
        </template>
        <v-list>
          <v-list-item>
            <v-list-item-title><v-icon>mdi-account</v-icon> My profile</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title><v-icon>mdi-history</v-icon> Order history</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title><v-icon>mdi-set-center</v-icon> Settings</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-menu>
    </v-app-bar>
  </v-card>
</div>
</template>

<script>
  export default {
    name: 'Header',

    data(){
      return{
      }
    },
  }
</script>
