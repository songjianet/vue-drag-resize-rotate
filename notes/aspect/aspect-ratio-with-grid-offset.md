# 在偏移的网格上对齐

使用`lock-aspect-ratio`时，在网格上使用组件的成本并不是很好。 您可以通过拖动（例如右手柄或底部手柄）来注意到您有不同的结果。

~~~js
<vue-drag-resize-rotate :lock-aspect-ratio="true" :grid=[20,20]>
  <p>Keep aspect ratio in component costrained on grid.</p>
</vue-drag-resize-rotate>
~~~

