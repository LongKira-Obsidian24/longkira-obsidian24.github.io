---
title: "Start"
date: "`r Sys.Date()`"
weight: 1
chapter: false
# pre: "<b>  </b>"
---

#### Đây là nơi chúng ta gọi là "nhà"

<div style="grid-template-columns: 1fr 1fr 1fr 1fr; margin: 0 auto;">
    <div class="container" style="width: 240px; display: inline-block; padding: 0px 3px 0px;">
        <a href="https://longkira-obsidian24.github.io/Instruction-Notes-Public/">
            <div class="overlay">
                <div class="text">Lorem friggin Ipsum</div>
            </div>
            <img src="/images/test/tile.jpg" alt="Tile" style="margin: 0 auto;">
        </a>
    </div>
    <div class="container" style="width: 240px; display: inline-block; padding: 0px 3px 0px;">
        <a href="/vi/start">
            <div class="overlay">
                <div class="text">Hello Za Warudo</div>
            </div>
            <img src="/images/test/tile.jpg" alt="Tile" style="margin: 0 auto;">
        </a>
    </div>
</div>

<style>
.image {
  width: 100%;
  height: auto;
}

.overlay {
  position: absolute;
  bottom: 100%;
  left: 0;
  right: 0;
  background-color: #000000;
  overflow: hidden;
  width: 100%;
  height: 0;
  transition: .5s ease;
}

.container:hover .overlay {
  bottom: 0;
  height: 100%;
}

.text {
  white-space: nowrap; 
  color: white;
  font-size: 20px;
  position: absolute;
  overflow: hidden;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}
</style>