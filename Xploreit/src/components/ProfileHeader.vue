<template>
    <div>
        <section class="profile-header">
        <button type="submit" class="back-button">
            <RouterLink to="/"><img src="/imagini/back.png" alt="Back"></RouterLink>
        </button>
        <div class="profile-img">
            <img src="/imagini/c1.jpg" alt="Profile Picture">
        </div>
        <div class="profile-info">
            <h1>Emma Roberts </h1>
            <div class="profile-rating">
                <img src="/imagini/star1.png" alt="Star">
                <img src="/imagini/star1.png" alt="Star">
                <img src="/imagini/star1.png" alt="Star">
                <img src="/imagini/start.png" alt="Star">
                <img src="/imagini/start.png" alt="Star">
            </div> <br>
            <button type="submit" class="message-button">
                <RouterLink to="/message">Send a message</RouterLink>
            </button>
        </div>
    </section>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

.profile-header {
    display: flex;
    align-items: center;
    padding: 20px 0;
    border-bottom: 1px solid #ddd;
    margin-bottom: 20px;
}

.back-button {
    background-color: transparent;
    border: none;
    cursor: pointer;
    margin-right: 20px;
}

.back-button img {
    width: 30px;
    height: auto;
}

.profile-img {
    margin-right: 20px;
}

.profile-img img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;
}

.profile-info {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

.profile-info h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

.profile-rating {
    display: flex;
    margin-bottom: 10px;
}

.profile-rating img {
    width: 30px;
    height: auto;
    margin-right: 5px;
}

.message-button {
    background-color: #000044;
    color: #fff;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
    text-align: center;
}

.message-button a {
    color: #fff;
    text-decoration: none;
}

</style>