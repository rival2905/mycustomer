<template>
    <div class="btn rounded border text-white bg-primary align-center" style="height:40px; width:40px"><center>{{nama}}</center></div>
</template>

<script>

export default {
    name: "CustomerLogo",

    props:['name'],
    
    data: function(){
        return{
            nama : this.name.substring(0,2),
        }
    }
    
}
</script>