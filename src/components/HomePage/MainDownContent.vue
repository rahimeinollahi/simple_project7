<template>
    <div class="bg-light" >
        <div class="d-flex flex-column justify-content-center mt-3">
            <i class="fa fa-home"></i>
            <h4>Match with companies.</h4>
            <h6>Select the top 3 values you want most in an employer.</h6>
        </div>
        <div class="row text-center justify-content-center" >
                <div id="emp-route" class="col-sm-3 border mx-2 mt-3 mb-4 p-3" v-for="item in employerItems" :key="item.id">
                    <router-link :to="item.itemPath" class=" nav-link  text-info ">{{item.name}}</router-link>
                </div>
         </div>
         <div class="d-flex flex-row justify-content-center">
             <button class="btn-info btn mb-5">See company match</button>
         </div>
    </div>
</template>

<script>
    export default {
        name:"MainDownContent",
        data(){
            return{
                employerItems:[
                    {id:1, name:"Above market salary", itemPath:'/about'},
                    {id:1, name:"collabrative", itemPath:'/about'},
                    {id:1, name:"Community Engagment", itemPath:'/about'},
                    {id:1, name:"Diversity + Inclustion", itemPath:'/about'},
                    {id:1, name:"Size of company", itemPath:'/about'},
                    {id:1, name:"Social Work Envirment", itemPath:'/about'},
                    {id:1, name:"work life Balance", itemPath:'/about'},
                    {id:1, name:"Technology Stack", itemPath:'/about'},
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
#emp-route{
    background-color: #fff;
}
</style>