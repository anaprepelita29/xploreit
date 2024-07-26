<template>
    <footer>
        <p>&copy;2024 All rights reserved.</p>
        <ul>
            <button><img src="/imagini/f.png" alt="Facebook"></button>
            <button><img src="/imagini/ig.png" alt="Instagram"></button>
        </ul>
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
footer {
    background-color: #2a2a72;
    color: #fff;
    padding: 20px 30px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 95%;
    position: static;
    bottom: 0;
}

footer p {
    margin: 0;
}

footer ul {
    list-style: none;
    display: block;
}

footer ul button {
    background: none;
    border: none;
    height: 30px;
}

footer ul button img {
    height: 40px;
}
</style>