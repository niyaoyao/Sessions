#  Objective-C Runtime : From Build To Did Launch
## Build, Compile & Archive
### Objective-C 语言特性
### Build 都做了些什么
#### Compile
##### Clang, GCC & G\++
##### 预处理 clang -E main.m
##### 语法和语义分析
##### 生成代码和优化 （xcrun） clang -S -o - main.m
##### 汇编器
##### 链接器
#### Mach-O
### Archive
#### Auto Archive
#### fastlane
## objc4 源码研读
## Runtime 应用场景
### AOP
### 动态埋点
### APM
