<template>
    <div>
        <h2>Online-friends</h2>
          <div v-for="(friends,index) in friends" :key="index">
            <span v-if="friends.online">{{friends.name}}</span>
          </div>
    </div>
</template>
<script>
export default {
    name:'OnlineFriends',
    data(){
        return {
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

</style>