<template>

<div class="address-overview-container">
            

            <ul class="grid-block">
              <li>Address</li>
              <li>{{account.address}}</li>
              
              <li>Wan Balance</li>
              <li>{{account.balance}}</li>
              
            </ul>
        
      </div>
</template>


<script lang="ts">
import Vue from 'vue';

 export default Vue.extend({
  name: 'Address',
  props: [
    'account'
  ],
  data() {
    return { 
    }
  },
  methods: {},
  computed: {}
})

</script>



<style scoped="" lang="less">
  @import "~lessPath/sunil/frames/address.less";
</style>
  
 