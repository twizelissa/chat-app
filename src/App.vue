<template>
  <div id="app">
  <h3>{{title}}</h3>
  <Navbar/>
  <AllFriends :friends="friends"/>
  <OnlineFriends :friends="friends"/>
  </div>
</template>

<script>

import Navbar from './Navbar'
import AllFriends from './AllFriends'
import OnlineFriends from './OnlineFriends'
export default {
  name: 'app',
  components:{
 Navbar,AllFriends,OnlineFriends
  },
  data () {
    return {
     title:" Real time app",
     friends:[
            {name:'Edisor',online:true},
            {name:'Anick',online:false},
            {name:'Alison',online:true},
            {name:'Mario',online:false}
        ]
    }
  }
}
</script>

<style>
h3{
  color: #4444;
  text-align: center;
  font-weight: normal;
}
</style>
