---
layout: page
title: Resume
permalink: /resume/
weight: 3
---

<button id="buttonA">English</button>
<button id="buttonB">中文</button>

<div id="objectA" style="display:none;">
    <object data="../assets/path/to/document.pdf" width="1000" height="1000" type='application/pdf'></object>
</div>

<div id="objectB" style="display:none;">
    <object data="../assets/path/to/潘逸铭简历（中）.pdf" width="1000" height="1000" type='application/pdf'></object>
</div>


<style>
#buttonA, #buttonB {
    display: inline-block; /* Ensure buttons are inline */
}
</style>

<script>
    document.getElementById("buttonA").addEventListener("click", function() {
    document.getElementById("objectA").style.display = "block"; // Show A
    document.getElementById("objectB").style.display = "none";  // Hide B
});

document.getElementById("buttonB").addEventListener("click", function() {
    document.getElementById("objectB").style.display = "block"; // Show B
    document.getElementById("objectA").style.display = "none";  // Hide A
});
</script>