<template>
    <div id="jumbo">

        <div id="jumbo_title">
            <h1>This is my hero banner!</h1>
            <p>(fantasia portami via)</p>
        </div>
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    #jumbo {
        background-image: url("../assets/jumbo.png");
        color: white;
        text-align: center;
        height: 500px;
        font-family: 'Montserrat', sans-serif;

        #jumbo_title {
            position: absolute;
            bottom: 10px;
            right: 20px;
        }

        p {
        font-size: 10px;
        }
    }   

</style>