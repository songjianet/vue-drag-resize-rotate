# 组件拖动取消的基本组件

一个基本组件，无法通过句柄拖动，由prop <b>`drag-cancel` </b>和有效的CSS选择器来指定，该范围无法将无法拖动组件。

~~~js
<vue-drag-resize-rotate style="border: 1px solid black;" :drag-cancel="'.drag-cancel'">
  <div class="drag-cancel">Cannot Drag Here</div>
</vue-drag-resize-rotate>
~~~

