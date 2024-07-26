<template>

    
    <ProfileHeader/>
    <ProfileCompletedTask />
    <ProfileTask />
</template>

<script>
import ProfileHeader from '@/components/ProfileHeader.vue';
import ProfileTask from '@/components/ProfileTask.vue';
import ProfileCompletedTask from '@/components/ProfileCompletedTask.vue';
export default {
components: {
    ProfileHeader,
    ProfileTask,
    ProfileCompletedTask
},
}
</script>

<style scoped>

</style>