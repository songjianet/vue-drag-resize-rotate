# 调整大小时具有自定义类名的组件

调整大小时具有自定义类名的组件，由prop <b>`class-name-resizing` </b>提供。

~~~js
<template>
<vue-drag-resize-rotate class-name-resizing="my-resizing-class" class-name="my-class">
  <p>You can provide a default class name for the component when it's resizing using the <b>class-name-resizing</b> prop.</p>
</vue-drag-resize-rotate>
</template>
<style>
.my-class {
    background-color: green;
    border: 1px solid red;
    -webkit-transition: background-color 200ms linear;
    -ms-transition: background-color 200ms linear;
    transition: background-color 200ms linear;
}

.my-resizing-class {
    background-color: blue;
    border: 1px solid black;
    color: white;
}
</style>
~~~

