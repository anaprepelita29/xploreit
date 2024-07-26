<template>
    <div class="chat-container">
<MessSideBar />
<MessMessage />
    </div>
</template>

<script>

import MessSideBar from '@/components/MessSideBar.vue';
import MessMessage from '@/components/MessMessage.vue';
    export default {
        components: {
            MessSideBar,
            MessMessage
        },
    }
</script>

<style scoped>
.chat-container {
    width: 100%;
    height: 600px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    display: flex;
    overflow: hidden;
    margin-top: 50px;
}

</style>