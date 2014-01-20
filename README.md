Steps:
1. 解析当前bundle的依赖bundle；
2. 对每个bundle进行打包；
2.1 根据menifest生成build.gradle文件
2.2. 执行gradle compile
2.3 move jar to eclipse/dropin
3. 生成当前bundle的launch文件；
