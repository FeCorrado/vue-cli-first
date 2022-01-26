<template>
    <div>
        <div class="big-box">
            <img class="grey" src="https://unsplash.it/600?image=235" alt="">
            <div class="titoli">
                <h1 class="bianco font1"><b>Lorem ipsum dolor sit amet, consectetur adipisicing elit. </b></h1>
                <div class="small bianco font1">Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque aperiam facere debitis rem evenie</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
.big-box{
    height: 400px;
    margin: auto;
    position: relative;
    border-radius: 4px;
    display: flex;
    justify-content: center;
}

.grey{
    opacity: 0.4;
    width: 1000px;
    height: 400px;
}

.titoli{
    bottom: 30px;
    position: absolute;
    width: 600px;
}

.font1{
    font-family:  'Montserrat', sans-serif;
    color: white;
    text-shadow: 2px 2px 5px black;
}

.small{
    font-size: 15px;
}


</style>