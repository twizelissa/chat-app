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
     props:["friends"],
    data(){
        return {
        
        }
    }
}
</script>
<style>

</style>