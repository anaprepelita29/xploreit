<template>
        <div class="sidebar">
                <div class="container">
                    <RouterLink to="/"><button class="buton"><img src="/imagini/back.png" alt="back" class="img-buton"></button></RouterLink>
                    <div class="text">Message</div>
                </div>
                <div class="user">
                    <img src="/imagini/c1.jpg" alt="User">
                    <div class="text">
                        <div class="username">Emma Roberts</div>
                        <div class="message">Loremhohihi ihoih...<br>hjljjjjjjjjjjjjjj...</div>
                    </div>
                </div>
                <div class="user">
                    <img src="/imagini/c1.jpg" alt="User">
                    <div class="text">
                        <div class="username">Emma Roberts</div>
                        <div class="message">Loremhohihi ihoih...<br>hjljjjjjjjjjjjjjj...</div>
                    </div>
                </div>
                <div class="user">
                    <img src="/imagini/c1.jpg" alt="User">
                    <div class="text">
                        <div class="username">Emma Roberts</div>
                        <div class="message">Loremhohihi ihoih...<br>hjljjjjjjjjjjjjjj...</div>
                    </div>
                </div>
                <div class="user">
                    <img src="/imagini/c1.jpg" alt="User">
                    <div class="text">
                        <div class="username">Emma Roberts</div>
                        <div class="message">Loremhohihi ihoih...<br>hjljjjjjjjjjjjjjj...</div>
                    </div>
                </div>
                <div class="user">
                    <img src="/imagini/c1.jpg" alt="User">
                    <div class="text">
                        <div class="username">Emma Roberts</div>
                        <div class="message">Loremhohihi ihoih...<br>hjljjjjjjjjjjjjjj...</div>
                    </div>
                </div>
            </div>

</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.sidebar {
    width: 30%;
    background-color: #f0f0f0;
    padding: 10px;
    box-sizing: border-box;
    overflow-y: auto;
    border-right: 1px solid #ddd;
}
.sidebar .container {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-bottom: 20px;
    border-radius: 5px;
    background-color: #e0e0e0;
}
.sidebar .container .text {
    flex: 1;
    font-size: 18px;
   margin-left: 20px;
}
.img-buton{
    height: 50px; 
    width: 50px;
}

.sidebar .container .button {
    padding: 10px 20px;
    font-size: 16px;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.sidebar .user {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
    padding: 5px;
    border-radius: 5px;
    cursor: pointer;
}
.sidebar .user:hover {
    background-color: #ddd;
}
.sidebar .user img {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    margin-right: 10px;
}
.sidebar .user .text {
    flex: 1;
}

</style>