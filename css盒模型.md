### css盒子模型

#### css盒模型分为IE盒模型和W3C标准盒模型

- W3C标准盒模型：属性width和height只包含content，不包含border和padding

- IE盒模型：属性width和height包含content+border+padding

box-sizing属性可以控制如何计算一个元素的width和height属性

box-sizing属性的值有:
- content-box：CSS标准指定的初始值和默认值，设置width和height属性只包含content，不包含padding、border和margin。
- border-box：width和height包含content、padding和border。
