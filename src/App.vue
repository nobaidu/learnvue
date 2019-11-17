<template>
  <div id="app">
    <Head />
	<Content />
  </div>
</template>

<script>
import Head from './components/Head.vue'
import Content from './components/Content.vue'

export default {
  name: 'app',
  components: {
    Head,
	Content
  }
}
</script>

<style>
/* common */
.width-100 {
    width: 100%;
}

.width-100wv {
    width: 100vw;
}

.height-100vh {
    height: 100vh;
}

.width-1200 {
    width: 12rem;
}

.height-auto {
    height: auto;
}

.height-100 {
    height: 100%;
}

.relative {
    position: relative;
}

.absolute {
    position: absolute;
}

.fixed {
    position: fixed;
}

.top-0 {
    top: 0;
}

.left-0 {
    left: 0;
}

.bottom-0 {
    bottom: 0;
}

.right-0 {
    right: 0;
}

.block {
    display: block;
}

.none {
    display: none;
}

.flex {
    display: flex;
}

.inline-block {
    display: inline-block;
}

.overflow-hidden {
    overflow: hidden;
}

.overflow-visible {
    overflow: visible;
}

.margin-0 {
    margin: 0;
}

.margin-auto {
    margin: auto;
}

.margin-0-auto {
    margin: 0 auto;
}


.float-left {
    float: left;
}

.float-right {
    float: right;
}

.clear-both {
    clear: both;
}

.color-fff {
    color: #ffff;
}

.color-000 {
    color: #000;
}

.size14 {
    font-size: 0.14rem;
}

.bold {
    font-weight: bold;
}

.text-left {
    text-align: left;
}

.text-center {
    text-align: center;
}

.text-right {
    text-align: right;
}

.vertical-top {
    vertical-align: top;
}

.vertical-middle {
    vertical-align: middle;
}

.vertical-bottom {
    vertical-align: bottom;
}

.border-box {
    box-sizing: border-box;
}

.content-box {
    box-sizing: content-box;
}

.transition3s {
    transition: all 0.3s;
}

.space-between {
    justify-content: space-between;
}

.space-around {
    justify-content: space-around;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 8px;
  max-width: 100%;
  overflow: hidden;
  box-sizing: border-box;
}

</style>
