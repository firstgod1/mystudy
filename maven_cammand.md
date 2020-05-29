# maven常用的命令
## a)clean: 清理，编译后的目录
## b)compile:  编译，只编译main目录，不编译test中的代码
## c)test-compile: 编译test中的代码
## d)test:          运行test里边的代码
## e)package:       打包
 ### i.java 项目->打成jar包
 ### ii. web项目-》打成war包
## f) install: 发布项目到本地仓库，用在打jar包上，打成jar包可以被其他项目使用
## g)tomcat:run 构建项目
# scop依赖作用域也可称作依赖范围：maven中的依赖，会根据程序中所处的阶段和场景发生变化，所以maven用scope属性来做限制；
## a)compile(默认值)：在编译、运行、测试、打包都有效；
## b)provided:编译、测试时有效，运行、打包无效；
## c）test：仅在测试时有效
## d)runtime：测试、运行、打包时有效；
## e)system:不推荐使用，使用system作用域不会去本地仓库寻找依赖，要指定本地路径
