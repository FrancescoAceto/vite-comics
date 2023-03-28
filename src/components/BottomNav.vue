<script>
export default { 
    name: 'BottomNav',
    data() {
        return {
            BottomNavImages: [
        {
          img: "footer-facebook.png",
        },
        {
          img: "footer-periscope.png",
        },
        {
          img: "footer-pinterest.png",
        },
        {
          img: "footer-twitter.png",
        },
        {
          img: "footer-youtube.png",
        },
            ],
        }
    },
}
</script>

<template>
    <div id="navbar-container">
        <div>
            <button>SIGN UP!</button>
        </div>

        <div id="span-container">
            <div v-for="BottomNavImages in BottomNavImages">
                <div>{{ BottomNavImages.img}}</div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
#navbar-container {
    display: flex;
    justify-content: space-around;
    align-items: center;

    background-color: #303030;
    color: black;

    padding: 1%;
}

#navbar-container button{
    background-color: #303030;
    color: white;
    border-color: rgb(0, 153, 255);
    padding: 10px;
}

#span-container{
    display: flex;
    gap: 15px;
    padding: 10px;
}

</style>