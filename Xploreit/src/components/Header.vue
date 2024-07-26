<template>
    <header>
        <nav>
            <div class="login">
                <RouterLink to="/"><img src="/imagini/logo.png.png"></RouterLink>
                <ul>
                    <li><RouterLink to="/profile">Profile</RouterLink></li>
                    <li><RouterLink to="/message">Messages</RouterLink></li>
                    <li>
                        <RouterLink to="/signin">Sign in</RouterLink>
                    </li>
                    <li><RouterLink to="/login">Login</RouterLink></li>

                </ul>
            </div>

        </nav>
    </header>
</template>

<script>
import { RouterLink } from "vue-router";

export default {

    components: {
        RouterLink,
    },

}
</script>

<style scoped>
header {
    background-color: rgb(255, 255, 255);
    border-bottom: 1px solid #ccc;
    padding: 0.5px 1px;
}

nav {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 0px;
}

nav .login {
    display: flex;
    align-items: flex-end;
    width: 100%;
    justify-content: space-between;
    list-style-type: none;
}



nav .login a {
    text-decoration: none;
    color: #000;
    font-family: Arial, sans-serif;
}

nav .login ul {
    display: flex;
    list-style: none;
    margin: 20px;
    padding: 0;
}

nav .login ul li {
    margin: 0px 10px;
}

nav .login ul li a {
    padding: 8px 16px;
    color: #000;
    font-size: 19px;
    transition: background-color 0.3s ease;
}

nav .login ul li a:hover {
    background-color: #f0f0f0;
    border-radius: 5px;
}

nav .login img {
    height: 50px;
}

nav .login button {
    background: none;
    border: none;
    cursor: pointer;
}

nav .login button img {
    height: 30px;
}
</style>