<script>
export default { 
    name: 'Navbar',
    data() {
        return {
            NavbarLinks: [
        {
          text: 'CHARACTERS',
        },
        {
          text: 'COMICS',
        },
        {
          text: 'MOVIES',
        },
        {
          text: 'TV',
        },
        {
          text: 'GAMES',
        },
        {
          text: 'COLLECTIBLES',
        },
        {
          text: 'VIDEOS',
        },
        {
          text: 'FANS',
        },
        {
          text: 'NEWS',
        },
        {
          text: 'SHOP',
        },
            ],
        }
    },
}
</script>

<template>
    <div id="navbar-container">
        <div>
            <img src="../../public/img/dc-logo.png" alt="">
        </div>

        <div id="span-container">
            <div v-for="NavbarLinks in NavbarLinks">
                <div>{{ NavbarLinks.text }}</div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
#navbar-container {
    display: flex;
    justify-content: space-around;
    align-items: center;

    background-color: white;
    color: black;

    padding: 1%;
}

#span-container{
    display: flex;
    gap: 15px;
    padding: 10px;
}

</style>