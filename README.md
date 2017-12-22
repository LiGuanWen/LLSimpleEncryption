# LLSimpleEncryption
 
 ios 代码加密 自动加密 根据方法或者属性的前缀进行自动加密 或者 对某些特定的方法或者属性进行加密 
 参考 https://www.jianshu.com/p/3fc444c1d40e

加密思路为： 通过confuse.sh在运行时会自动匹配代码方法或者属性中包含某个规定的前缀（lgw_） 生成随机的字符串 存放在codeObfuscation.h 中 相对于宏定义 然后进行替换 
