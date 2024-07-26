<template>
    <div class="form-container">
        <form action="/login" method="post">
            <input type="text" id="username" name="username" placeholder="Username" required>
            <input type="password" id="password" name="password" placeholder="Enter password" required>
            <button type="submit">Login</button>
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
    height: calc(100vh - 150px);
    margin-top: 100px;
}

form {
    background-color: #f9f9f9;
    padding: 30px;
    border: 1px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 350px; /* crește dimensiunea formularului */
    display: flex;
    flex-direction: column;
    align-items: center;
}

form input {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    width: 80%;
    padding: 10px;
    background-color: #2a2a72;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
}

form button:hover {
    background-color: #1e1e5c;
}
</style>