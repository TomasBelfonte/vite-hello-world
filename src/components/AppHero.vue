<template lang="">
    <div>
        <h1>{{userDetail()}}</h1>
    </div>
</template>
<script>
export default {
    data () {
        return {
            user: {
                nomeUtente: "Tomas",
                cognomeUtente: "Belfonte",
                role: "Studente Classe 79"
            }            
        };
    },

    methods: {
        userDetail () {
            return this.user.nomeUtente + " " +this.user.cognomeUtente + " " + this.user.role;
        }
    },
};
</script>
<style lang="">
    
</style>