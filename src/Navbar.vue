<template>
    <nav>
        <ul>
            <li><a href="www.facebook.com">Facebook</a></li>
            <li><a href="www.twitter.com">Twitter</a></li>
            <li><a href="www.linkedin.com">Linkedin</a></li>

        </ul>
    </nav>
</template>
<script>
export default {
    name:'Navbar',
    props:["friends"],
    data(){
        return {

        }
    }
}
</script>
<style>
nav{
    background-color: rgb(129, 129, 167);
    text-align: center;
    line-height: 70px;
}
nav ul{
padding: 0;
 
}
nav li{
    margin: 5px;
    color: rgb(236, 236, 241);
    display: inline-block;
    font-size: 20px;
    text-decoration: none;
    list-style-type: none;
    
}

</style>