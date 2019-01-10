# vue-watermark

> 网页水印

### Build Setup 使用步骤

``` bash
# 安装 install
yarn add vue-watermark --save
```
``` bash
# 使用 use
--script
import WaterMark from 'vue-watermark'
export default {
  name: 'App',
  components: {
    WaterMark
  }
}

--html
<pic-zoom></pic-zoom>
```
### Config 配置
props | describe | default
----|------|----
user | 当前用户  | string null
company | 公司名称 | string null
time | 是否启用时间戳  | boolean fasle 

### Author

Jeffery Gou.