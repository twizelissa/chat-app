<template>
    <div>
        <h2>All-Friends</h2>
        <div v-for="(friends,index) in friends" :key="index">
            <span>{{friends.name}}</span>
        </div>
    </div>
</template>
<script>
export default {
    name:'AllFriends',
    props:['friends'],
    data(){
        return {
     
        }
    }
}
</script>
<style>

</style>