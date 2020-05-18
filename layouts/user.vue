<template>
<div>
    <div>
        <v-toolbar dark prominent src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg">
            <v-app-bar-nav-icon></v-app-bar-nav-icon>
            <v-toolbar-title>Vuetify</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-btn icon>
                <v-icon>mdi-export</v-icon>
            </v-btn>
        </v-toolbar>
    </div>
    <div style="background: url('https://images.unsplash.com/photo-1549740425-5e9ed4d8cd34?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80');background-repeat: no-repeat;background-size: cover;">
        <v-hover open-delay="200">
            <v-container :fluid=true>
                <v-row align="center">
                    <v-col cols="12" sm="12" md="12">
                        <v-responsive class="overflow-y-auto" max-height="400">
                          <nuxt />
                        </v-responsive>
                    </v-col>
                </v-row>
            </v-container>
        </v-hover>
    </div>
</div>
</template>

<script>
export default {
    name: '',
    data() {
        return {
            hover: true,
        }
    }
}
</script>
