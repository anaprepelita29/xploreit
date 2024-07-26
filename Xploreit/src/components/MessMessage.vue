<template>

    <div class="chat-box">
        <div class="header">
            <img src="/imagini/c1.jpg" alt="User">
            <div>
                <div class="username">Emma Roberts</div>
                <div class="user-id">(emma_123)</div>
            </div>
        </div>
        <div class="messages">
            <div class="message sent">
                <div class="text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque facere blanditiis quod nobis dolor!
                </div>
            </div>
            <div class="message received">
                <div class="text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque facere blanditiis quod nobis dolor!
                </div>
            </div>
            <div class="message sent">
                <div class="text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque facere blanditiis quod nobis dolor!
                </div>
            </div>
            <div class="message received">
                <div class="text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque facere blanditiis quod nobis dolor!
                </div>
            </div>
        </div>
        <div class="input-container">
            <input type="text" placeholder="Message...">
            <button>Send</button>
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>
.chat-box {
    width: 70%;
    display: flex;
    flex-direction: column;
}
.header {
    display: flex;
    align-items: center;
    padding: 10px;
    background-color: #f5f5f5;
    border-bottom: 1px solid #ddd;
}
.header img {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    margin-right: 10px;
}
.header .username {
    font-weight: bold;
}
.header .user-id {
    color: #777;
}

.messages {
    flex: 1;
    padding: 10px;
    overflow-y: auto;
}

.message {
    display: flex;
    margin-bottom: 10px;
}

.message.sent {
    justify-content: flex-end;
}

.message.received .text {
    background-color: #e0e0e0;
}

.message.sent .text {
    background-color: #c8e6c9;
}

.message .text {
    max-width: 70%;
    padding: 10px;
    border-radius: 10px;
}

.input-container {
    display: flex;
    padding: 10px;
    border-top: 1px solid #ddd;
}

.input-container input {
    flex: 1;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 20px;
    margin-right: 10px;
}

.input-container button {
    padding: 5px;
    border: none;
    border-radius: 20px;
    cursor: pointer;

}

.img-buton {
    height: 50px;
    width: 50px;
}

.section {
    width: 100%;
    margin-bottom: 50px;
}

.buton {
    border: none;
    cursor: pointer;
}
</style>