<template>
 <div class="container">
   <div class="row">
     <div class="col-xs-12">
       <app-quote>
         <H1 slot="title"> {{ quoteTitle }}</H1>
         <p slot="content">Good to see you today</p>
       </app-quote>
     </div>
   </div>
 </div>
</template>

<script>
import Quote from './components/Quote.vue';

  export default {
    data:function() {
      return {
        quoteTitle:'Hello World!'
      }
    },
    components: {
      appQuote: Quote
    }
  }
</script>

<style>

</style>
