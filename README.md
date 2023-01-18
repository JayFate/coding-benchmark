# coding-benchmark

### 测试维度

- 品牌
  - 机型
    - 配置
      - 前端
        - vue
          - Vue core
          - Vue 应用
        - React 
          - React 仓库
          - React 应用
        - Nodejs 工具
      - Java
      - Go
      - C++
      - Python

### 测试流程

```txt
npx envinfo
getDate getTime
time start
分项的time start
分项的time end
轻度负载性能测试
编译脚本每一项测试项跑5轮
重度负载性能测试
每一项里面都并行运行
编译脚本每一项测试项跑30轮
time end
```

