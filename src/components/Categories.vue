<template>
    <div class="content" style="width:100%" align="center">
        <h3>Browse Categories</h3>
        <v-col>
        <v-row align="center" style="width:70%" class="my-3" justify="space-between">
            <v-card class="mx-auto" width="31%">
                <v-list >
                    <v-subheader>Stress Relief</v-subheader>
                    <v-list-item-group color="primary">
                        <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content style="text-align:left">
                            <v-list-item-title v-text="item.text"></v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-card>
            <v-card class="mx-auto" width="31%">
                 <v-list >
                    <v-subheader>Dry Cough</v-subheader>
                    <v-list-item-group color="primary">
                        <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content style="text-align:left">
                            <v-list-item-title v-text="item.text"></v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-card>
            <v-card class="mx-auto" width="31%">
                 <v-list >
                    <v-subheader>Appetizers</v-subheader>
                    <v-list-item-group color="primary">
                        <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content style="text-align:left">
                            <v-list-item-title v-text="item.text"></v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-card>
        </v-row>
        <v-row align="center" style="width:70%" class="my-3" justify="space-between">
            <v-card class="mx-auto" width="31%">
                <v-list >
                    <v-subheader>Malaria & Typhoid</v-subheader>
                    <v-list-item-group color="primary">
                        <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content style="text-align:left">
                            <v-list-item-title v-text="item.text"></v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-card>
            <v-card class="mx-auto" width="31%" >
                 <v-list >
                    <v-subheader>Acne and Marks</v-subheader>
                    <v-list-item-group color="primary">
                        <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content style="text-align:left">
                            <v-list-item-title v-text="item.text"></v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-card>
            <v-card class="mx-auto" width="31%">
                 <v-list >
                    <v-subheader>Ear and Eye</v-subheader>
                    <v-list-item-group color="primary">
                        <v-list-item v-for="(item, i) in items" :key="i">
                        <v-list-item-content style="text-align:left">
                            <v-list-item-title v-text="item.text"></v-list-item-title>
                        </v-list-item-content>
                        </v-list-item>
                    </v-list-item-group>
                </v-list>
            </v-card>
        </v-row>
        </v-col>
    </div>
</template>

<script>

export default ({
    name: 'Categories',
    data:() =>{
      return ({
        items: [
            { text: 'Real-Time', icon: 'mdi-clock' },
            { text: 'Audience', icon: 'mdi-account' },
            { text: 'Conversions', icon: 'mdi-flag' },
        ],
        });
    }
})
</script>

<style >

</style>