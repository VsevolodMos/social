<template>
  <v-app id="app">
    <v-navigation-drawer
       color="green"
        dark
        expand-on-hover
        hide overlay
        permament
        right
        app
       >
        <v-list
      nav 
      shaped
      dense
     >
     <v-list-item two-line>
      <v-list-item-avatar>
         <img :src="'https://randomuser.me/api/portraits/men/7.jpg'"> 
      </v-list-item-avatar>

      <v-list-item-content class="text-left">
         <v-list-item-title class="font-weight-black">SocialLink</v-list-item-title>
         <v-list-item-subtitle>Иван Иванов</v-list-item-subtitle>
      </v-list-item-content>
     </v-list-item>
    <v-divider class="my-3"></v-divider>
    
    

      <v-list-item-icon>
        <v-icon>mdi-home-outline</v-icon>
      </v-list-item-icon>

      <v-list-item-content>
        <router-link to="/about"><v-list-item-title class="text-left">Главная</v-list-item-title></router-link>
      </v-list-item-content>

    

    <v-list-item link :to="путь">

      <v-list-item-icon>
        <v-icon>mdi-account</v-icon>
      </v-list-item-icon>

      <v-list-item-content>
        <v-list-item-title class="text-left">Мой профиль</v-list-item-title>
      </v-list-item-content>

    </v-list-item>

    <v-list-item link :to="путь">

      <v-list-item-icon>
        <v-icon>mdi-account-multiple-plus-outline</v-icon>
      </v-list-item-icon>

      <v-list-item-content>
        <v-list-item-title class="text-left">Найти друзей</v-list-item-title>
      </v-list-item-content>

    </v-list-item>

    </v-list>
    </v-navigation-drawer>
    
    <v-content class="px-12 py-3">
      <v-container fluid>
          <div>
        <v-row class="text-left">
            <v-col cols="10">
                <h1 class="green--text text--darken-2">
                    <v-icon large color="green darken-2">mdi-account-outline</v-icon>
                    Иван Иванов
                </h1>
            </v-col>
        </v-row>
        <v-row class="text-left">
            <v-col cols="2">
                <img src="https://randomuser.me/api/portraits/men/7.jpg" style="max-width: 100%">
            </v-col>
            <v-col cols="10" class="text-left">
                <p>
                    Веб-сайт: <a href="http://jsonplaceholder.typicode.com/users/7" target="_blank">...</a>
                </p>
                <p>
                    E-mail: <a href="mailto:...">...</a>
                </p>
                <p>
                    Город: ...
                </p>
                <p>
                    Место работы: ...
                </p>
            </v-col>
        </v-row>

        
    </div>
    <v-divider class="my-3"></v-divider>
    <h2 class="green--text text--darken-2 py-5"> Публикации </h2>
    <v-card
      max-width="900"
      class="mx-auto" 

    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">Our Changing Planet</v-list-item-title>
          <v-list-item-subtitle>by Kurt Wagner</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
  
     
  
      <v-card-text>
        Visit ten places on our planet that are undergoing the biggest changes today.
      </v-card-text>
  
      <v-card-actions>
        
        <v-spacer></v-spacer>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
                  <v-icon>mdi-bookmark</v-icon>
                </v-btn>
  
        <v-btn icon>
          <v-icon>mdi-share-variant</v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>
    <v-card
      max-width="900"
      class="mx-auto my-10" 

    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">Our Changing Planet</v-list-item-title>
          <v-list-item-subtitle>by Kurt Wagner</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
  
     
  
      <v-card-text>
        Visit ten places on our planet that are undergoing the biggest changes today.
      </v-card-text>
  
      <v-card-actions>
        
        <v-spacer></v-spacer>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
                  <v-icon>mdi-bookmark</v-icon>
                </v-btn>
  
        <v-btn icon>
          <v-icon>mdi-share-variant</v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>
    <v-card
      max-width="900"
      class="mx-auto my-10" 

    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">Our Changing Planet</v-list-item-title>
          <v-list-item-subtitle>by Kurt Wagner</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
  
     
  
      <v-card-text>
        Visit ten places on our planet that are undergoing the biggest changes today.
      </v-card-text>
  
      <v-card-actions>
        
        <v-spacer></v-spacer>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
                  <v-icon>mdi-bookmark</v-icon>
                </v-btn>
  
        <v-btn icon>
          <v-icon>mdi-share-variant</v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>
    <v-card
      max-width="900"
      class="mx-auto my-10" 

    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">Our Changing Planet</v-list-item-title>
          <v-list-item-subtitle>by Kurt Wagner</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
  
     
  
      <v-card-text>
        Visit ten places on our planet that are undergoing the biggest changes today.
      </v-card-text>
  
      <v-card-actions>
        
        <v-spacer></v-spacer>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
                  <v-icon>mdi-bookmark</v-icon>
                </v-btn>
  
        <v-btn icon>
          <v-icon>mdi-share-variant</v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>
    <v-card
      max-width="900"
      class="mx-auto my-10" 

    >
      <v-list-item>
        <v-list-item-avatar color="grey"></v-list-item-avatar>
        <v-list-item-content>
          <v-list-item-title class="headline">Our Changing Planet</v-list-item-title>
          <v-list-item-subtitle>by Kurt Wagner</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
  
     
  
      <v-card-text>
        Visit ten places on our planet that are undergoing the biggest changes today.
      </v-card-text>
  
      <v-card-actions>
        
        <v-spacer></v-spacer>
        <v-btn icon>
          <v-icon>mdi-heart</v-icon>
        </v-btn>
        <v-btn icon>
                  <v-icon>mdi-bookmark</v-icon>
                </v-btn>
  
        <v-btn icon>
          <v-icon>mdi-share-variant</v-icon>
        </v-btn>
      </v-card-actions>
    </v-card>

      </v-container>
    </v-content>
   <router-view/>
  </v-app>
</template>

<script>


export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>
