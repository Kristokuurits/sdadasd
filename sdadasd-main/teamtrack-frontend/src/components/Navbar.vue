<template>
    <div class="topnav">
        <a class="active" href="/">Home</a>
        <a href="/coachEvents">Coachevents</a>
        <a href="/athleteEvents">Athleteevents</a>
        <a href="/coachEvents">AddEventForm</a>
    </div>

    <div style="padding-left:16px">
    </div>
</template>

<script lang="ts">

</script>

<style scoped>
    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
    }

    .topnav {
        overflow: hidden;
        background-color: black;
    }

        .topnav a {
            float: left;
            color: #ff0000;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 17px;
        }

            .topnav a:hover {
                background-color: #ddd;
                color: black;
            }

            .topnav a.active {
                background-color: #04AA6D;
                color: red;
            }
</style>
