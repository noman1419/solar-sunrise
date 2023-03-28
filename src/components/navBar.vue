<template>
  <div class="hello">
    <div class="navBar">
        <div class="logo">
            <img src="../assets/logo.svg" alt="logo"/>
        </div>
        <div class="nav-list">
            <ul class="a">
                <li><a href="#Home">Home</a></li>
                <li><a href="#About">About</a></li>
                <li><a href="#FAQ">FAQ</a></li>
                <li><a href="#Contact-Us">Contact Us</a></li>
                <li><a href="#Qoute" id="qoute">Get a Quote</a></li>
            </ul>
        </div>
    </div>
  </div>
</template>
<style scoped>
.hello{
    padding: 0 20px;
}
.hello{
    font-size: 16px;
}
.navBar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 80px;
    border-bottom: 1px solid #000;
}
.logo img{
    height: 80px;
}
.nav-list ul{
    display: flex;
}
ul.a{
    list-style-type: none;
}
ul li a{
    padding: 10px;
    color: black;
    text-decoration: none;
}
#qoute{
    border: 1px solid black;
}
hr{
    width: 95%;
}
</style>
