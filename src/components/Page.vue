<template>
    <div class="flex justify-between p-5 pb-10">
        <div class="leftside pt-10">
            <div class="text-white text-4xl text-left font-bold">
                <h2>Work hard in Silence let your</h2>
                <h2>success be your noise.</h2>
            </div>

            <div class="text-white text-lg text-left mt-6">
                <p>A stronger learner and healthier you is the goal of every fitness</p>
                <p>training program at grynd, from personal training to pilates to </p>
                <p>small groups programs.</p>
            </div>
            <div class="getbutton w-52  h-12 mt-12 rounded-full flex flex-wrap content-center justify-center">
                <p class="text-white text-xs font-bold">Get started</p>
            </div>
        </div>
        <div class="rightside">
            <img src="../assets/HeroBg.svg" alt="background" class="svgbg">
            <img src="../assets/Image01.png" alt="Fit" class="womanpic" >
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>
 <style scoped>
 * {
     font-family: 'Oswald', sans-serif;
 }

 .getbutton {
    background: #e0ab8b;
 }

 .leftside {
    background: url('../assets/BgImage.png');
    
    background-repeat:no-repeat;
    background-position: center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    min-height: 60vh;
    padding-bottom: 0;
 }

.svgbg {
  opacity: 0.6;
  position: absolute;
  left: 55%;
  top: 20%;
  width: 50vw;
  height: 400px;
}

  .womanpic {
      position: relative;
     /* background: url(/../assets/Image01.svg); */
    background-repeat:no-repeat;
    background-position: center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    height: 500px;
    margin-top: -80px;
 }

 </style>