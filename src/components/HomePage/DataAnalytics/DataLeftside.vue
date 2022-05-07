<template>
    <div id="data-leftside" class="text-white p-3">
        <h3 class="font-weight-bold">Fully managed data pipelines</h3>
        <div class="d-flex flex-column">
            <div class="embed-responsive embed-responsive-16by9 "> 
                <video width="320" height="240" controls class="w-100">
                    <source src="../../../videos/video1.mp4" type="video/mp4" class="">
                </video>
            </div>
        </div> 

        <div class="d-block text-start">
            <span><img src="../../../assets/ok.png" alt="ok icon" style="width:20px"></span>
            <span class="display-5 text-white">Adapts with your data</span>
            <p>New fields and API versions are automatically updated</p>
        </div>
        
        <div class="d-block text-start">
            <span><img src="../../../assets/ok.png" alt="ok icon" style="width:20px"></span>
            <span class="display-5 text-white">Easy to set up</span>
            <p>All data sources have simple authentication fields</p>
        </div>

        <div class="d-block text-start">
            <span><img src="../../../assets/ok.png" alt="ok icon" style="width:20px"></span>
            <span class="display-5 text-white">Reliable</span>
            <p>Automated retries are picked up from the last saved sync</p>
        </div>

    </div>
</template>

<script>
    export default {
        name:"DataLeftSide"
    }
</script>

<style lang="scss" scoped>
#data-leftside{
        background-color: rgb(0, 43, 236);
    }

</style>