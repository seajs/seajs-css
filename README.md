seajs-css
=========

A Sea.js plugin for loading css

Install
-------

Install with spm:

    $ spm install seajs/seajs-css


Usage
-----

```html
<script src="path/to/sea.js"></script>
<script src="path/to/seajs-css.js"></script>

<script>

// seajs can load css file after loading style plugin.
seajs.use("path/to/some.css")

</script>
```

### 中文说明

* 在Sea.js < 2.3.0版本之前是可以加载css文件的，新版本中此功能移除，为了兼容考虑，加载css功能将作为一个插件存在。
* 使用方法
  * 可以在sea.js标签后引入这个插件使用
  * 也可以将插件代码混入sea.js当中
* 和seajs-style的区别
  * seajs-css是加载一个纯css文件，和link标签一样
  * seajs-style是指加载一段包裹成seajs.importStyle的css，文件是个js