---
layout: page
title: Resume
permalink: /resume/
weight: 3
---

<!-- HTML !-->
<div class="button-container">
    <button class="button-54" role="button" id="buttonA">English</button>
    <button class="button-54" role="button" id="buttonB">中文</button>
</div>

<object id="objectA" style="display:block;margin-top:1vh" data="../materials/Yiming Pan Resume.pdf" width="1000" height="1000" type='application/pdf'></object>

<object id="objectB" style="display:none;margin-top:1vh" data="../materials/潘逸铭简历（中）.pdf" width="1000" height="1000" type='application/pdf'></object>

<style>
#buttonA, #buttonB {
    display: inline-block; /* Ensure buttons are inline */
}

.button-container {
    display: flex;
    justify-content: center; /* Center horizontally */
    align-items: center; /* Center vertically */
}

/* CSS */
.button-54 {
  font-family: "Open Sans", sans-serif;
  font-size: 16px;
  letter-spacing: 2px;
  text-decoration: none;
  text-transform: uppercase;
  color: #000;
  cursor: pointer;
  border: 3px solid;
  padding: 0.25em 0.5em;
  box-shadow: 1px 1px 0px 0px, 2px 2px 0px 0px, 3px 3px 0px 0px, 4px 4px 0px 0px, 5px 5px 0px 0px;
  position: relative;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

.button-54:active {
  box-shadow: 0px 0px 0px 0px;
  top: 5px;
  left: 5px;
}

@media (min-width: 768px) {
  .button-54 {
    padding: 0.25em 0.75em;
  }
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