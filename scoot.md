---
permalink: scoot/index.html
title: Scoot
layout: pages
---

<center>
var images = [
    "/Images/Rotato/1.jpg",
    "/Images/Rotato/2.jpg",
    "/Images/Rotato/3.jpg",
    "/Images/Rotato/4.jpg",
    "/Images/Rotato/5.jpg"];

function randImg() {
    var size = images.length
    var x = Math.floor(size * Math.random())
    document.getElementById('image').src = images[x];
}

randImg();
</center>
