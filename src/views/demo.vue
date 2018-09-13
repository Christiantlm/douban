<template>
  <div>
  <div>{{info}}</div>
   <div><input type="text" v-model="info"></div>
   <div><button id="test" type="button" v-on:click="test">test</button></div>
  </div>
 
</template>

<script>
import { mapState } from 'vuex'

export default {
  name: 'demo-view',

  data () {
    return {
        info:"asdsad"
    }
  },
  computed: {
    ...mapState({
      
    })
  },
  methods: {
    
  },
  created: function created () {
 
  }
}
</script>