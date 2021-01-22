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