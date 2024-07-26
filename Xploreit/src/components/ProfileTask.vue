<template>
<section class="taskuri">
        <section class="lista-clase">
            <div class="task-list">
                <div class="task-item">
                    <h4>Nina Dobrev:</h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque facere blanditiis quod nobis
                        dolorum! Accusamus dignissimos quibusdam repellat cupiditate nemo atque excepturi magnam,
                        consectetur, aliquam dolorem earum, impedit ea eaque!</p>
                    <p class="violet">4.5 rate 3 hours-spent Difficulty: Hard</p>
                </div>
            </div>
        </section>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.taskuri {
    width: 100%;
    padding: 20px;
    margin-right: 70px;
}

.lista-clase {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}

.task-list {
    flex: 1 1 calc(33.333% - 20px);
    display: flex;
    justify-content: center;
}

.task-item {
    background-color: #5272ff42;
    border: 1px solid #00004447;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 100%;
}

.task-item h4 {
    margin-bottom: 10px;
}

.task-item p {
    margin: 10px 0;
}

.violet {
    color: #000044;
}
</style>