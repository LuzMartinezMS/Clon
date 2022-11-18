<template>
     <nav>
            <img class="logo" id="logo" src="https://www.gstatic.com/devrel-devsite/prod/vefe830b4ddbb6fbf9f8f84fc45bd4079738c13cea1a4dbeb400bd711e695c305/firebase/images/lockup.svg" alt="FirebaseLogo"></img>
            <div class="dropdown">
                <button class="dropbtn">Products</button>
                <div class="dropdown-content">
                    <a href="#">Build</a>
                    <a href="#">Release & Monitor</a>
                    <a href="#">Engage</a>
                </div>
            </div>

            <div class="dropdown">
                <button class="dropbtn">Solutions</button>
                <div class="dropdown-content">
                    <a href="#">Explore all solutions<br>Discover solutions for use<br>cases in your apps and<br>businesses</a>
                </div>
            </div>


            <div class="dropdown">
                <button class="dropbtn">Pricing</button>
                <div class="dropdown-content">
                    <a href="#">Link 1</a>
                </div>
            </div>

            <div class="dropdown">
                <button class="dropbtn">Docs</button>
                <div class="dropdown-content">
                    <a href="#">Overview</a>
                    <a href="#">Fundamentals</a>
                    <a href="#">Build</a>
                    <a href="#">Release & Monitor</a>
                    <a href="#">Engage</a>
                    <a href="#">Reference</a>
                    <a href="#">Samples</a>
                </div>
            </div>

            <div class="dropdown">
                <button class="dropbtn">More</button>
                <div class="dropdown-content">
                    <a href="#">Community</a>
                    <a href="#">Support</a>
                </div>
            </div>

            <input class="search" type="text" placeholder="Search">
            <button class="console">Go to console</button>
            <button class="signIn">Sign in</button>
        </nav>
</template>

<script>
    export default{
        name:'navBar',
    }
</script>

<style scoped>
nav{
    background-color: white;
    -webkit-box-shadow: -1px 9px 12px -9px rgba(54,61,74,0.85);
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    padding-bottom: 5px;
    margin-top: 10px;
}

.logo{
    width: 100px;
}
/* Dropdown Button */
.dropbtn {
  background-color: #ffffff;
  color: rgb(125, 125, 125);
  padding: 0px;
  font-size: 12px;
  border: none;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #ffffff;
  font-size: 10px;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {color: rgb(158, 158, 158);}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {color:black;}

.search{
    background-color: #f3f3f3;
    border-color: transparent;
    border-radius: 5px;
    width: 150px;
    height: 18px;
}

.console{
    background-color: transparent;
    color:#1a73e8;
    border-color: transparent;
    border-radius: 5px;
    
}


.signIn{
    background-color: transparent;
    color:#1a73e8;
    border-color: transparent;
    border-radius: 5px;
    
}

.console:hover{
    background-color: #d2e3fc;
    
}

.signIn:hover{
    background-color: #d2e3fc;
    
}
</style>