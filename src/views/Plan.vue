<template>
<div id="container">

<div class="col" id="col1">
    <h2>Data Journalism</h2>
    <p>National News</p>
    <p>Elections</p>
    <p>Travel</p>
    <p>Big City Events</p>
    <p>Contextual Data for News</p>

    <p>January</p>
    <p>February</p>
    <p>March</p>
    <p>April</p>
    <p>May</p>

    <p>Deep Dives - Texas Grid</p>
    <p>Energy in America</p>
    <p>Where food comes from</p>

    <p>National - updated data</p>
    <p>Economy</p>
    


    <p>Covid - Deep Dives</p>

    <!-- <img src="./assets/transmission_by_county_image.PNG"/> -->

</div>
<div class="col" id="col2">
    <h2>10 Selected Cities</h2>
    <p>Start creating maps connected to useful government data. Daily crime, restaurant health scores, public projects/construction, etc. </p>
</div>
<div class="col" id="col3">
    <h2>25 cities</h2>
    <p>moving guide</p>
    <p>50 travel guides</p>
    <p>Best Trails in each city</p>
    <p>Music Tours</p>
    <p>Breweries in each city</p>

</div>
<div class="col" id="col4">
    <h2>Citizens</h2>
    <p>Jobs - Indeed API</p>
    <p>Homes</p>


</div>


</div>
</template>

<script>


export default {
  name: 'Plan',
}
</script>

<style scoped>
#container{
    margin-left:260px;
    display: grid;
    grid-template-rows: 1fr;
    grid-template-columns: 25% 25% 25% 25%;
}

.col{
    padding:15px;
}

#col1{
grid-column: 1/2;
height:80vh;
border-right: 1px solid navy;
}



#col2{
    height:80vh;
    grid-column: 2/3;
    border-right: 1px solid navy;
}

#col3{
    height:80vh;
    grid-column: 3/4;
    border-right: 1px solid navy;
}

#col4{
    height:80vh;
    grid-column: 4/5;
}
h2{
    text-align: center;
}
img{
    width:85%;
}

</style>
