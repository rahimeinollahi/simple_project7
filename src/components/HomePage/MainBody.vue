<template>
    <div id="mainBody" class="container mt-1 p-5">
        <div class="d-flex justify-content-center">
            <img  src='../../assets/bag.png'/>
        </div>

        <div class="d-block text-white">
            <h2 class="text-white">Match with jobs.</h2>
            <p>Enter your expertise + skills to view jobs that are right for you.</p>
        </div>

        <div class="row text-white">
            <div class="col-md-6 d-flex flex-row justify-content-center">
                <form action="" class="w-50 mt-2 mb-2">
                <label for="expertise" class="">core Expertise</label>
                    <select class="form-select  text-center" id="sel-exp" name="sel-exp">
                        <option value="ُSelect Expertise">Select Expertise</option>
                        <option value="content"> Contetn</option>
                        <option value="Data Analytics">Data Analytices</option>
                        <option value="Design UX">Design Ux</option>
                        <option value="financ">Finance</option>
                    </select>
                </form>
            </div>

            <div class="col-md-6 d-flex flex-row justify-content-center">
                <form action="" class="w-50 mt-2 mb-2">
                        <label for="year-expt">Year of Experience</label>
                        <select name="year-epxt" id="year-epxt" class="form-select text-center ">
                            <option value="1-3 years">1-3 years</option>
                            <option value="3-5 years">1-3 years</option>
                            <option value="5-8 years">1-3 years</option>
                            <option value="more than 10 years">1-3 years</option>
                        </select>
                </form>

            </div>
        </div>
            <router-link to="/" class="nav-link text-white font-weight-bold">NO, I’M NOT INTERESTED IN JOB OFFERS RIGHT NOW</router-link>
    </div>
</template>

<script>
    export default {
        name:'MainBody'
    }
</script>

<style lang="scss" scoped>
#mainBody{
    background-color: rgb(60, 197, 231);
}
</style>