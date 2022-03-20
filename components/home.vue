<template>
    <main>
        <div class="content">
    <div class="text-content">
        <div class="text">WELCOME TO</div>
            <div class="name">Good_Style</div>
                <div class="job">
                    <div class="job">
                        <span>I'am Supplied A</span>
                        <div class="typing-text">
                            <span class="one">T Shirt,</span>
                            <span class="two">Distro.</span>
                        </div>
                    </div>
                </div>
    </div>
</div>
    </main>
</template>

<style scoped>
.text-content{
    position: absolute;
    top: 2cm;
    left: 1cm;
    z-index: 12;
}
.text-content .text{
    font-size: 27px;
    color: #2c3350;
    font-weight: bold;
}
.text-content .name{
    color: #2c3350;
    font-size: 75px;
    font-weight: 600;
    margin: -20px 0 0 -3px;
}
.text-content .job{
    color: #2c3350;
    font-size: 20px;
    font-family: sans-serif;
    font-weight: bold;
    margin: 2px 0px;
    margin-top: -5px;
    display: flex;
}
.text-content .typing-text{
    
    margin-left: 5px;
    overflow: hidden;
    white-space: nowrap;
    border-right: 4px solid #000000;
    animation: typing 5s steps(15) infinite;
}
@keyframes typing{
    0%{
    width: 0ch;
    }
    50%{
    width: 12ch;
    }
    100%{
    width: 0ch;
    }
}
.text-content .job .one{
    color: #0400ff;
}
.text-content .job .two{
    color: #00ff22;
}
</style>