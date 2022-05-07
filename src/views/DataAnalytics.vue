<template>
    <div class="container mt-3">
        <div class="row">
            <div class="col-md-6">
                <data-leftside />
            </div>
            <div class="col-md-6">
                <data-rightside />
            </div>
        </div>
    </div>
</template>

<script>
import DataLeftside from '../components/HomePage/DataAnalytics/DataLeftside.vue'
import DataRightside from '../components/HomePage/DataAnalytics/DataRightside.vue'
    export default {
  components: { DataLeftside, DataRightside },
        
    }
</script>

<style lang="scss" scoped>

</style>