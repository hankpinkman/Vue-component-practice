<template>
<div>
    <p>
    Lamp Status : {{ status }}
    </p>
    <button @click="openLamp">Open Lamp</button>
</div>
</template>
<script>
export default {
    data : function(){
        return {
        status : "Off" 
        }
    },
    methods : {
        openLamp(){
            this.status = "Open..."
        }

    }
}
</script>