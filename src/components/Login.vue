<template>

<div class="container card mt-4 ">
<input type="text" placeholder="Enter email"  v-model="email"/>
<br>
<br>
<input type="text" placeholder="Enter password" v-model="password"/>
<br>
<br>
<button type="submit" placeholder="Login" v-on:click="getDetails()">Submit your Details</button>

</div>
</template>
    
<script>
export default {
        name:"Login",
        data(){
            return{
                    email:null,
                    password:null

            }
        },
        methods:{

            getDetails(){

                console.log("Details given", this.email,this.password)

            }
        }
}
</script>
<style scoped>

</style>