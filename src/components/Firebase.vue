<template>
    <body>


        
        <navBar/>

        <div class="main">

            <div class="d1">
                <div class="d2">
                    <div class="d3">
                        <h2 class="h2-1">Make your app the <br> best it can be</h2>
                        <p class="p1">Firebase is an app development platform that<br> helps you build and grow apps and games<br> users love. Backed by Google and trusted by <br> millions of businesses around the world.</p>
                        <div class="buttons">
                            <button class="getStarted">Get started</button>
                            <a class="demo">Try demo</a>
                            <a class="wvideo">Watch video</a>
                        </div>
                    </div>
                    <video src="https://firebase.google.com/static/images/homepage/Firebase_Hero_Loop_1440x735.webm" autoplay muted loop></video>
                </div>   
            </div>

            <div class="d1-1">
                <div class="d2-1">
                    <p>Products and solutions you can rely on through your</p>
                    <p>app's journey</p>
                  
                </div>
                <div class="d3-1">
                    <div class="products">
                        <img class="icons" src="https://firebase.google.com/static/images/homepage/home-icon-build_2x.png"></img>
                        <div class="p-texts">
                            <p class="t1">Build</p>
                            <p class="t2">Accelerate app development</p>
                            <p class="t2">with fully managed backend</p>
                            <p class="t2">infrastructure</p>
                            <p class="t3">View all build products</p>

                        </div>
                        <div class="p-icons">

                        </div>
                    </div>


                    <div class="products">
                        <img class="icons" src="https://firebase.google.com/static/images/homepage/home-icon-release_2x.png"></img>
                        <div class="p-texts">
                            <p class="t1">Release & Monitor</p>
                            <p class="t2">Release with confidence and</p>
                            <p class="t2">monitor performance and</p>
                            <p class="t2">stability.</p>
                            <p class="t3">View all releases & monitor</p>
                            <p class="t3-1">products</p>
                        </div>
                        <div class="p-icons">
                        </div>
                    </div>


                    <div class="products">
                        <img class="icons" src="https://firebase.google.com/static/images/homepage/home-icon-engage_2x.png"></img>
                        <div class="p-texts">
                            <p class="t1">Engage</p>
                            <p class="t2">Boost user engagement with</p>
                            <p class="t2">rich analythics, A/B testing, and</p>
                            <p class="t2">messaging campaigns</p>
                            <p class="t3">View all engage products</p>

                        </div>
                        <div class="p-icons">

                        </div>

                    </div>
                </div>
                <div></div>
                <div></div>
            </div>

        </div>

    </body>
</template>

<script>

import navBar from '../components/navBar.vue'
export default {
  name: 'Firebase',
  components:{
    navBar,
  }
}


</script>

<style scoped>

*{
    font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
}

body{

    background-color: #1a73e8;
    width: 100 vw;
    height: 100 vh;
    margin: 0px;
    padding: 0px;
}



.main{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.d1{
    display: flex;
    flex-direction: column;
    width: 900px;
}

.d2{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    color: white;
}

.d3{

    display: flex;
    flex-direction: column;

}

.logo{
    width: 100px;
}

.h2-1{
    margin-top: 50px;
    font-size: 40px;
}

.p1{
    font-size: 20px;
    margin-top: 0px;
}

.demo{
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 12px;
    font-weight: bold;
    width: 60px;
    height: 30px;
    border-radius: 5px;
}

.wvideo{
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 12px;
    font-weight: bold;
    width: 80px;
    height: 30px;
    border-radius: 5px;
}


video{
    width: 380px;
}

.getStarted{
    background-color: white;
    color:#1a73e8;
    font-size: 18px;
    border-color: transparent;
    border-radius: 5px;
    width: 150px;
    height: 40px;
}

.buttons{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    align-items: center;
    margin-top: 10px;
}



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

.getStarted:hover{
    background-color: #d2e3fc;

}

.demo:hover{
    background-color: rgba(111, 145, 210, 0.85);

}

.wvideo:hover{
    background-color: rgba(111, 145, 210, 0.85);

}

.d1-1{
    margin-top: 100px;
    width: 800px;
    height: 1200px;
    border-radius: 10px;
    background-color: white;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.d2-1{
    display: flex;
    flex-direction: column;
    align-items: center;
    color: #37474f;
    font-size: 25px;
    font-weight: bold;
    margin-top: 50px;
}

.d2-1>p{
    margin: 0px;
}

.d3-1{
    display:flex;
    flex-direction: row;
    justify-content: space-around;
    width: 700px;
    margin-top: 40px;

}

.products{
    
    background-color: rgb(248, 249, 250);
    border-radius: 10px;
    width: 210px;
    height: 420px;
    -webkit-box-shadow: 1px 2px 5px 0px rgb(185, 185, 185);
    padding-top: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.products:hover{
    background-color: rgb(210,227,252);
}

.icons{
    width: 110px;
}

.p-texts{
    display: flex;
    flex-direction: column;
    align-items: center;
}

.t1{
    color:#37474f;
    font-size: 20px;
    font-weight: bold;
}

.t2{
    color:#6d838f;
    font-size:12px;
    font-weight: lighter;
    margin:2px;
}

.t3{
    color:#1967D2;
    font-size:13px;
    font-weight: bold;
    margin-top:15px;
}

.t3-1{
    color:#1967D2;
    font-size:13px;
    font-weight: bold;
    margin-top:-10px;
}

</style>