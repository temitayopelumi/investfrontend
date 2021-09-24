<template>
    <v-card
        max-width="400"
    >
        
        <ImageEl src="https://cdn.vuetifyjs.com/images/cards/docks.jpg" height="200" />

        <v-card-subtitle class="pb-0">
            Land at Ikeja
        </v-card-subtitle>

        <v-card-text class="text--primary">
            <div>&#8358; 20,000</div>
            <div>20km</div>
            <div>
                Description Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,
                molestiae quas vel sint commodi repudia
            </div>
        </v-card-text>

        <v-card-actions>
            <v-btn
                color="primary"
                text
            >
                More details
            </v-btn>
            <v-spacer></v-spacer>
            <v-btn
                color="success"
                text to="update-asset"
            >
                Edit
            </v-btn>
        </v-card-actions>
    </v-card>
</template>

<script>
    import ImageEl from "@/components/ImageEl.vue"
    export default {
        components:{
            ImageEl
        }
    }
</script>