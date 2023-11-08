<script setup lang="ts">
import * as PIXI from "pixi.js"
//创建一个应用
const app=new PIXI.Application({
width:window.innerWidth,
height:window.innerHeight,
background:  0x16999b,
resolution:window.devicePixelRatio || 1
})
document.body.appendChild(app.view)
const rectTangle=new PIXI.Graphics()
rectTangle.beginFill('red')
rectTangle.drawCircle(200,100,30)
rectTangle.endFill()
app.stage.addChild(rectTangle)
</script>

<template>
  <div></div>
</template>

<style scoped>

</style>
