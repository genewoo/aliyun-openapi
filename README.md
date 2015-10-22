# aliyun-openapi


# 设计思路

设计底层的DSL封装对API的访问，对错误的封装以及返回数据的解析

把一个一个的分类API按照子包的形式载入，例如

```ruby

require 'aliyun-openapi/ess'
require 'aliyun-openapi/bss'

```

