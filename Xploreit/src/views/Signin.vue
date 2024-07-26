<template>
    <div class="form-container">
        <form action="/login" method="post">
            <input type="text" id="username" name="username" placeholder="Username" required>
            <input type="password" id="password" name="password" placeholder="Create a password" required>
            <input type="password" id="re-password" name="re-password" placeholder="Re-enter the password" required>
            <button type="submit">Sign in</button>
        </form>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.form-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh;
    width: 100%;
    margin-top: 100px;
}

form {
    background-color: #f9f9f9;
    padding: 30px;
    border: 1px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 350px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

form input {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    width: 100%;
    padding: 10px;
    background-color: #3d3d84;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    margin-top: 10px;
}

form button:hover {
    background-color: #2a2a63;
}
</style>