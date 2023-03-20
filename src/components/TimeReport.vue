<template>
    <div id="main">
        <div class="container">
            <div class="profile-box">
                <div class="profile">
                    <img src="@/assets/image-jeremy.png" alt="" class="jeremy">
                    <p class="report-for">Report for</p>
                    <h1 class="robson">JEREMY ROBSON</h1>
                </div>
                <div class="report">
                    <p class="report-days-1">Daily</p>
                    <p class="report-days">Weekly</p>
                    <p class="report-days">Monthly</p>
                </div>
            </div>
            <div id="routine">
                <div class="schedule-box">
                    <div class="visuals">
                        <img src="@/assets/icon-work.svg" alt="work" class="work">
                    </div>
                    <div class="event">
                        <p class="activity">Work</p>
                        <h1 class="hours">32hrs</h1>
                        <p class="duration">Last Week - 5hrs</p>
                        <div class="switch">
                            <div class="circle"></div>
                            <div class="circle"></div>
                            <div class="circle"></div>
                        </div>
                    </div>
                </div>
                <div class="schedule-box">
                    <div class="visuals-2">
                        <img src="@/assets/icon-play.svg" alt="work" class="work">
                    </div>
                    <div class="event">
                        <p class="activity">Play</p>
                        <h1 class="hours">10hrs</h1>
                        <p class="duration">Last Week - 8hrs</p>
                        <div class="switch">
                            <div class="circle"></div>
                            <div class="circle"></div>
                            <div class="circle"></div>
                        </div>
                    </div>
                </div>
                <div class="schedule-box">
                    <div class="visuals-3">
                        <img src="@/assets/icon-study.svg" alt="work" class="work">
                    </div>
                    <div class="event">
                        <p class="activity">Study</p>
                        <h1 class="hours">4hrs</h1>
                        <p class="duration">Last Week - 7hrs</p>
                        <div class="switch">
                            <div class="circle"></div>
                            <div class="circle"></div>
                            <div class="circle"></div>
                        </div>
                    </div>
                </div>
                <div class="schedule-box">
                    <div class="visuals-4">
                        <img src="@/assets/icon-exercise.svg" alt="work" class="work">
                    </div>
                    <div class="event">
                        <p class="activity">Exercise</p>
                        <h1 class="hours">4hrs</h1>
                        <p class="duration">Last Week - 5hrs</p>
                        <div class="switch">
                            <div class="circle"></div>
                            <div class="circle"></div>
                            <div class="circle"></div>
                        </div>
                    </div>
                </div>
                <div class="schedule-box">
                    <div class="visuals-5">
                        <img src="@/assets/icon-social.svg" alt="work" class="work">
                    </div>
                    <div class="event">
                        <p class="activity">Social</p>
                        <h1 class="hours">5hrs</h1>
                        <p class="duration">Last Week - 10hrs</p>
                        <div class="switch">
                            <div class="circle"></div>
                            <div class="circle"></div>
                            <div class="circle"></div>
                        </div>
                    </div>
                </div>
                <div class="schedule-box">
                    <div class="visuals-6">
                        <img src="@/assets/icon-self-care.svg" alt="work" class="work">
                    </div>
                    <div class="event">
                        <p class="activity">Self Care</p>
                        <h1 class="hours">2hrs</h1>
                        <p class="duration">Last Week - 2hrs</p>
                        <div class="switch">
                            <div class="circle"></div>
                            <div class="circle"></div>
                            <div class="circle"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<script>
export default{
    
}
</script>

<style>
/* @import url('https://fonts.googleapis.com/css2?family=Barlow:ital,wght@0,600;1,600&family=DM+Sans:wght@500;700&family=Epilogue:ital,wght@0,500;0,700;1,500;1,700&family=Fraunces:opsz,wght@9..144,500;9..144,700&family=Inter:wght@400;700;800;900&family=Outfit:wght@300;400;600&family=Poppins:ital,wght@0,500;0,700;1,500;1,700&family=Rubik:wght@300;400;500&family=Ubuntu:wght@400;500;700&display=swap'); */
/* font-family: 'Rubik', sans-serif; */
/* - Blue: hsl(246, 80%, 60%) */

/* - Light red (work): hsl(15, 100%, 70%) */
/* - Soft blue (play): hsl(195, 74%, 62%) */
/* - Light red (study): hsl(348, 100%, 68%) */
/* - Lime green (exercise): hsl(145, 58%, 55%) */
/* - Violet (social): hsl(264, 64%, 52%) */
/* - Soft orange (self care): hsl(43, 84%, 65%) */

/* - Very dark blue: hsl(226, 43%, 10%) */
/* - Dark blue: hsl(235, 46%, 20%) */
/* - Desaturated blue: hsl(235, 45%, 61%) */
/* - Pale Blue: hsl(236, 100%, 87%) */

*{
    margin: 0;
    padding: 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    /* background-color: hsl(226, 43%, 10%); */
    box-sizing: border-box;
}
#main{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: hsl(226, 43%, 10%);
    height: 100vh;
}
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    /* width: 60em; */
    /* height: 30em; */
    /* background-color: hsl(226, 43%, 10%); */
    /* margin-top: 40px; */
    position: relative;
}
.profile{
    height: 14em;
    width: 11em;
    background-color: hsl(246, 80%, 60%);
    border-radius: 10px;
    position: absolute;
    top: 0.5rem;
}
.jeremy{
    border: 2px solid white;
    border-radius: 50%;
    width: 3.5em;
    height: 3.5em;
    margin: 1em;
    
}
.report-for{
    color: white;
    margin: 0.5em 1.2em;
    font-size: 13px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.robson{
    color: white;
    margin: 0.3em 0.7em;
    line-height: 30px;
    font-size: 1.5rem;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
 
}
.profile-box{
    position: relative;
    /* margin-left: 1em; */
    margin-right: 0.5em;
    height: 17em;
    width: 11em;
    cursor: pointer;
}
.report{
    height: 19em;
    width: 11em;
    background-color: hsl(235, 46%, 20%);
    border-radius: 10px;
    /* padding-top: 9.5rem; */
    margin-top: 2.5em;
    /* position: absolute; */
}
.report-days-1{
    line-height: 30px;
    color: hsl(0, 0%, 53%);
    margin: 5px 20px;
    padding-top: 12.3rem;
}
.report-days{
    line-height: 30px;
    color: hsl(0, 0%, 53%);
    margin: 5px 20px;
    /* display: flex; */
    /* margin-top: 25px; */
}
.report-days:hover, .report-days-1:hover{
    color: white;
}
.report-days:active, .report-days-1:active{
    color: rgb(255, 255, 255);
}
#routine{
    display: grid;
    grid-template-rows: repeat(2, 1fr);
    grid-template-columns: repeat(3, 1fr);
}
.schedule-box{
    position: relative;
    margin: 3em 0.5em;
    cursor: pointer;
    /* width: 10em; */
    /* height: 10em; */
}
.visuals{
    width: 11em;
    height: 5em;
    background-color: hsl(15, 100%, 70%);
    border-radius: 10px;
    display: flex;
    justify-content: end;
    /* position: absolute; */
    /* bottom: 8rem; */

}
.work{
    width: 3.5em;
    height: 3.5em;
    margin: 0 0.5em;
    object-position: 0 -0.5rem;
}
.event{
    width: 11em;
    height: 8.5em;
    border-radius: 10px;
    background-color: hsl(235, 46%, 20%);
    position: absolute;
    top: 1.5rem;
    color: white;
}
.event:hover{
    /* background-color: rgb(255, 254, 254); */
}
.activity{
    margin: 20px;
}
.hours{
    margin: 0 15px;
}
.duration{
    color: rgb(138, 138, 138);
    font-size: 10px;
    margin: 5px 20px;
}
.switch{
    position: absolute;
    right: 1.3rem;
    bottom: 6.2rem;
}
.circle{
    height: 5px;
    width: 5px;
    display: inline-block;
    margin: 1px;
    border-radius: 50%;
    background-color: rgb(255, 255, 255);
}
.visuals-2{
    width: 11em;
    height: 5em;
    background-color: hsl(195, 74%, 62%);
    border-radius: 10px;
    display: flex;
    justify-content: end;
}
.visuals-3{
    width: 11em;
    height: 5em;
    background-color: hsl(348, 100%, 68%);
    border-radius: 10px;
    display: flex;
    justify-content: end;
}
.visuals-4{
    width: 11em;
    height: 5em;
    background-color: hsl(145, 58%, 55%);
    border-radius: 10px;
    display: flex;
    justify-content: end;
}
.visuals-5{
    width: 11em;
    height: 5em;
    background-color: hsl(264, 64%, 52%);
    border-radius: 10px;
    display: flex;
    justify-content: end;
}
.visuals-6{
    width: 11em;
    height: 5em;
    background-color: hsl(43, 84%, 65%);
    border-radius: 10px;
    display: flex;
    justify-content: end;
}
@media only screen and (max-width: 375px){
    #main{
        background-color: hsl(226, 43%, 10%);
        height: 100em;
    }
    .container{
        flex-direction: column;
    }
    .profile{
        height: 8.5em;
        width: 20em;
        display: flex;
    }
    .jeremy{
        margin: 2.5em 1em;
    }
    .report-for{
        margin: 3.5em 0 0 0;
       }
    .robson{
        position: absolute;
        top: 3.5rem;
        left: 4.5rem;
    }
    .profile-box{
        position: relative;
        height: 10em;
        width: 20em;
        cursor: pointer;
    }
    .report{
        height: 10em;
        width: 20em;
        background-color: hsl(235, 46%, 20%);
        border-radius: 10px;
        /* padding-top: 9.5rem; */
        margin-top: 2em;
        display: flex;
        /* position: absolute; */
    }
    .report:hover{
        color: white;
    }
    .report-days:hover, .report-days-1:hover{
    color: white;
    }
    .report-days:active, .report-days-1:active{
        color: rgb(255, 255, 255);
    }
    .report-days-1{
        margin: 0 20px;
        padding-top: 7.5rem;
    }
    .report-days{
        margin: 7.5em 35px;
    }
    #routine{
        display: flex;
        flex-direction: column;
    }
    .schedule-box{
    margin: 3.5em 0.5em;
    }
    .visuals{
        width: 20em;
    }
    .event{
        width: 20.2em;
        top: 2rem;
        left: -1px;
    }
    .event:hover{
        /* background-color: rgb(255, 254, 254); */
    }
    .duration{
        font-size: 15px;
        position: absolute;
        right: 0.1rem;
        bottom: 2.5rem;
    }
    .visuals-2{
        width: 20em;
    }
    .visuals-3{
        width: 20em;
    }
    .visuals-4{
        width: 20em;
    }
    .visuals-5{
        width: 20em;
    }
    .visuals-6{
        width: 20em;
    }
}


</style>