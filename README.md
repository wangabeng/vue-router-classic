# vue-router-classic
经典实用的vue-router

关于"vue路由router-link to=/user/username/age/10 参数只能写死么？能不能写变量？"的问题
参见：https://www.vue-js.com/topic/58efa5505fa2416c039052d7
解答：
outer-link :to="{path:‘pathname‘,query: {key:value}}"
跳转过去的地址格式就是（http://…/pathname?key=value）
value作为一个变量可以在data里面定义
