TypeScript ts-node tsconfig-paths Demo
============================

在tsconfig.json中定义的`paths`仅供typescript类型检查使用。当它被编译成js时，并不会被替换，所以node无法直接执行。

ts-node配合`tsconfig-paths`使用，可以动态替换，在替换过程中不需要生成中间js文件

```
npm install
npm run demo
```
