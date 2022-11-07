<script>
export default{
    data(){
        return{
            message: "Ciao sono un jumbotron",
        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <img src="../assets/pexels-pixabay-163036.jpg" alt="">
        <div class="jumbo-message">
            <h1>{{ message }}</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, ipsa. Lorem ipsum dolor sit amet.</p>
        </div>
    </div>
</template>

<style>
.jumbotron{
    width: 100%;
    height: 500px;
    position: relative;
}

.jumbotron img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.jumbotron .jumbo-message{
    text-align: right;
    position: absolute;
    top: 10px;
    right: 25px;
    color: #fff;
}
</style>