# 内部系统bug提交

## [issue](https://github.com/sealyun-market/issues/issues)



### 提交Bug

label分类

- 所属模块  （area开头）
- issue类型 （bug还是feautre）
- 重要性 (重要性)
- 测试相关标签 （test相关）

开发测试流程：

1. 测试提相关bug需要打label(所属模块、issue类型、重要性)
2. 开发完成后需要加（need-ok-to-test）的标签，为了告诉测试这些可以进行测试流程
3. 测试完成后最终（ok-to-test和faild-to-test）两种，如果测试通过（ok-to-test）移除掉need-ok-to-test的标签，相反需要开发重复流程2。