<template>
    <div class="container mt-3">
        <ul class="nav nav-tab bg-light justify-content-center">

            <div v-for="item in mainNavItems" :key="item.id">
                <li class="nav-item dropdown p-3 " v-if="item.id==1">
                    <a href="#" class="nav-link dropdown-toggle" data-bs-toggle="dropdown">{{item.navName}}</a>
                    <ul class="dropdown-menu">
                        <li v-for="jobItem in item.itemsLink" :key="jobItem.id">
                            <router-link class="dropdown-item text-dark" :to="jobItem.navPath">{{jobItem.jobName}}</router-link>
                        </li>
                    </ul>
                </li>

                <li v-else class="nav-item p-3 ">
                    <router-link :to='item.navPath' class="nav-link  text-dark">{{item.navName}}</router-link>
                </li>
            </div>

            

        </ul>
    </div>
</template>

<script>
    export default {
        name:'MainNav',
        data(){
            return{
                mainNavItems:[
                    {id:1, navName:'Jobs',itemsLink:[
                        {id:11, jobName:'Data Analytices',navPath:'/dataanalytices'},
                        {id:12, jobName:'Design Ux',navPath:'/designux'},
                        {id:13, jobName:'Operations',navPath:'/operaion'},
                        {id:13, jobName:'Product',navPath:'/product'},
                        {id:13, jobName:'Marketing',navPath:'/marketing'},
                    ]},
                    {id:2, navName:'Tech Companies',navPath:'/techcompanies'},
                    {id:3, navName:'Remote',navPath:'/remote'},
                    {id:4, navName:'Tech Topic',navPath:'/techtopic'},
                    {id:5, navName:'Salaries',navPath:'/salaries'},
                    {id:6, navName:'Learn',navPath:'/learn'},
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>