---
title: Boston Routing
subtitle: a multi vehicle multi stop optimal routes solver
layout: page
show_sidebar: true
menubar: menu
hero_image: /brblog/img/vtjenne.jpg
hero_height: is-medium
---

<div class="columns is-multiline">
    <div class="column is-12 has-text-right">
        <a href="https://github.com/spearsear">
            <img src="https://img.shields.io/github/stars/chrisrhymes/bulma-block-list?style=social" alt="GitHub Stars" />
        </a>
        <a href="https://github.com/spearsear">
            <img alt="GitHub forks" src="https://img.shields.io/github/forks/chrisrhymes/bulma-block-list?label=fork&style=social">
        </a>
        <img alt="npm" src="https://img.shields.io/npm/dw/bulma-block-list">
    </div>

    <div class="column is-12">
        <div class="content">
            <h2 id="how-to-use">How to use</h2>
            <p>Visit the routing tool at <a href="http://bostonrouting.com">Boston Routing</a> and follow the instructions below:</p>
        </div>
        <div class="highlight highlight-text-html-basic">
            <ul class="is-left">
                <li>Click Start on main page</li>
                <li>Enter or load list of customer stops at the section below the map</li>
                <li>Enter one or more depots with their addresses at the section to the right of the map</li>
                <li>Enter one or more vehicles for each depot</li>
                <li>Enter a name for the problem and your email address at the section to the lower right of the screen</li>
                <li>Click Submit, then visit the link in a few minutes to see the routes generated.</li>
            </ul>
        </div>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="nearly-free">Nearly Free</p>
    </div>
    <div class="column is-12">
        <ul class="is-left">
            <li>Up to 200 stops free</li>
            <li>More than 200 stops we will be in touch</li>
            <li>This satisfy most of people</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="enter-list-of-stops">Enter List of Stops</p>
    </div>
    <div class="column is-12">
        <ul class="is-small">
            <li>Click "Add New Customer" to add one line in the customers table</li>
            <li>Click the "a name" row to modify the Name, Address etc</li>
            <li>Enter number of minutes at "Min" column as the duration at this stop</li>
            <li>Enter auantity of materials used at "Qty" column as the demand at this stop</li>
            <li>Enter ready time at "Rdy_Time" column as the earliest time you can start working at this stop</li>
            <li>Enter due time at "Due_Time" column as the latest time you have to start working at this stop</li>
            <li>Rdy_Time and Due_Time in format like "09:30 AM" without the quote</li>
            <li>Address will be automatically geocoded</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="upload-list-of-stops">Upload List of Stops</p>
    </div>
    <div class="column is-12">
        <ul class="is-primary">
            <li>Click "Download Customers CSV" to get a template csv file with the stops on screen</li>
            <li>Modify the downloaded csv template to enter your list of stops, leave the lat/lng empty if you don't have it</li>
            <li>Click "Upload Customers CSV" to select the csv file with list of stops</li>
            <li>Verify your list of stops on screen</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="demand-of-each-stop">Demand of Each Stop</p>
    </div>
    <div class="column is-12">
        <ul class="is-outlined is-primary">
            <li>Demand quantity at "Qty" column</li>
            <li>We do not care units of the demand</li>
            <li>For example, each stop demand 20 yards of mulch, you just enter 20</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="duration-of-each-stop">Duration of Each Stop</p>
    </div>
    <div class="column is-12">
        <ul class="has-radius is-primary">
            <li>Duration of each stop is the number of minutes</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="time-boxing-of-each-stop">Time Boxing of Each Stop</p>
        <p>You can specify a time frame when your vehicle needs to arrive at a certain stop</p>
    </div>
    <div class="column is-12">
        <ul class="">
            <li>You arrive between Rdy_Time and Due_Time</li>
            <li class="is-highlighted">Enter in format as "09:40 AM"</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="capacity-of-each-vehicle">Capacity of Each Vehicle</p>
        <p>If your vehicle deliver materials like mulch, enter total capacity of the vehicle</p>
    </div>
    <div class="column is-12">
        <ul class="">
            <li>Capacity(Minutes) is currently not used</li>
            <li>Enter Capacity(Quantity) as the capacity of the vehicle</li>
            <li class="is-large">Do NOT include units, we do not use that</li>
        </ul>
    </div>

    <div class="column is-12">
        <p class="title is-4" id="save-to-local">Save to Local</p>
    </div>
    <div class="column is-12">
        <ul class="is-small is-outlined is-success is-centered">
            <li>At top right of the screen, pull down "Problem"</li>
            <li>Select "Save to Local"</li>
            <li>It will save to your local drive a file with extension .vrp</li>
            <li>Later, you can "Load from Local" to load the vrp file back</li>
        </ul>
    </div>

    <div class="column is-12">
            <p class="title is-4" id="save-to-cloud">Save to Cloud</p>
    </div>
    <div class="column is-12">
        <ul class="is-small is-outlined is-success is-centered">
            <li>At bottom right of the screen, click "Submit" (or "Save")</li>
            <li>Your problem will be sent to our server</li>
            <li>We will reoptimize your routing problem if it has changed</li>
            <li>You will receive an email in a few minutes</li>
            <li>You can visit the link to see the routing by clicking the "Routes" tab</li>
        </ul>
    </div>
</div>