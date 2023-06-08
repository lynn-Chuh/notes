## 1. 相关技术
- jsx、State、事件处理等必备知识
- 状态提升、组件解耦、组合
- Refs转发
- 高阶组件
- Render Props
- 错误边界（Error Boundaries）

**React Hook**
- useState，useRef
- 自定义hook：异步操作、状态管理、debounce、路由、增删改查等

Hook + Context /Redux Toolkit 管理客户端全局状态
React Query 管理服务端全局状态
性能优化、性能监控、性能报告

## mock

- mockjs
通过修改http请求返回结果达到模拟数据的目的
优点：1.与前端代码分离，入侵少。2.可生成随机数据
缺点： 1.数据都是动态生成的假数据，无法真实模拟增删改查的情况。2. 仅支持ajax，不支持fetch

- 接口管理工具
  rap、swagger、moco、yapi
 优点：配置功能强大，接口管理与mock一致，后端修改接口mock也跟着更改，可靠。
 缺点：配置复杂，依赖后端。小团队一般很少用，等配置完了可能接口也写完了。
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg5MDAxNzA4NCwtMTYyNTQ1MzM3MSwtMT
YwNDQ5NDc1N119
-->