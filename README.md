# interview

## 提交规范
  - `feat` 增加新文档
  - `fix` 修复文档或代码bug
  - `style` 代码风格相关无影响运行结果的
  - `perf` 优化文档或代码
  - `refactor` 重构文件目录
  - `revert` 撤销修改
  - `docs` 文档/注释
  - `chore` 依赖更新/配置修改等


```ts
type Exclude<T, U> = T extends U ? never : T
type Pick<T, U extends keyof T> = {
  [k in U]: T[k]
}
```