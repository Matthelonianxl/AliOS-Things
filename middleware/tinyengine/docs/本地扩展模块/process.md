
# API

## process.version
* <strong><code>string</code></strong><strong>对象</strong>

## process.platform
* <strong><code>string</code></strong><strong>对象</strong>

## process.nextTick(callback)
* <strong><code>callback</code></strong><strong>  函数</strong>
在下一个事件循环中异步调用`callback`函数
__应用场景__
* 
## process.uptime()
* <strong>返回</strong><code><strong>number</strong></code><strong>,   表示系统开始运行到当前时刻的秒数</strong>

## __process.memoryUsage()__
* <strong>返回 </strong><code><strong>Ojbect</strong></code><strong> 对象， 表示当前BoneEngine使用符号表的情况</strong>
    * `heapTotal` [<integer>](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Number_type) 符号表总数
    * `heapUsed`   [<integer>](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Number_type) 符号表当前使用数目

 