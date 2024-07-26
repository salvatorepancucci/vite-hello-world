<template>
    <div class="jumbotron">
        <h1 class="display-4">Mambo Jumbo</h1>
        <p class="lead">Vite + Vue</p>
        <hr class="my-4">
        <p>Less is more!</p>
    </div>
</template>

<script>
export default {
    name: 'AppHero'
}
</script>

<style scoped>
.jumbotron {
    background: linear-gradient(135deg, #8e44ad 0%, #3498db 100%);
    padding: 60px 0;
    text-align: center;
    color: #fff;
    border-radius: 15px;
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
    margin: 20px auto;
    width: 600px;
}

.jumbotron .display-4 {
    font-size: 3rem;
    font-weight: 700;
    color: #fff;
}

.jumbotron .lead {
    font-size: 1.5rem;
    font-weight: 400;
    color: #f1c40f;
}

.jumbotron hr.my-4 {
    border-top: 1px solid #fff;
}

.jumbotron .btn-primary {
    background-color: #2ecc71;
    border: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 1rem;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.jumbotron .btn-primary:hover {
    background-color: #27ae60;
}
</style>
