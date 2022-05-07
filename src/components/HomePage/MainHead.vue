<template>
    <div class="container mt-1">
        <div class="bg-light d-flex justify-content-start p-4">
            <img src="../../assets/user.png" alt="logo main header" class="" style="width:70px">
            <div class="mx-3">
                <h3>hey rahim einollahi</h3>
                <router-link to="/updateprofile" class="nav-link text-danger">Update Your Profile</router-link>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'mainHead'
    }
</script>

<style lang="scss" scoped>
img{
    border-radius: 50%;
}
</style>