## VGT-ELEMENT-UI-THEME

`vue-good-table` is a powerful data table plugin for VueJS

Element-UI is a popular and frequently used Vue UI framework for building components 

But `vue-good-table` is limited in it's theming support.
Currently using vue-good-table with el-ui setup stands out as a separate standalone piece because of how it looks.

So I implemented the custom el-table theme for vgt to give it the same aesthetic look and feel as other components of the library

For using this just add these scss files and add prop `theme = 'el-table-them'` to vgt

```js
<vue-good-table theme="el-table-theme">
...
</vue-good-table>
```

For reference - [Theme](https://github.com/xaksis/vue-good-table/tree/master/src/styles/black-rhino)
