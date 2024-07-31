<script>
// import:
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';



export default {
   nome: 'App',
   components: {
      HeaderComponent,
      FooterComponent,
   }
}

</script>



<template>
  
   <!--? HEADER -->
   <HeaderComponent />
   
   <!--? CONTENT -->
   <router-view></router-view>
   
   <!--? FOOTER -->
   <FooterComponent />


</template>


<style lang="scss" scoped></style>
