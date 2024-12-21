# Agent实验



## 题目要求



实现一个只需要使用语言即可使用的选课系统，不包含任何GUI。被调用的函数可以使用copilot生成，不需要使用数据库，只需要能够模拟对应功能。

## 功能简介



1. 查询：带有筛选的查询，可以筛选必修或选修。
2. 选课：选择需要的课程，智能返回结果
   1. 成功返回选课结果
   2. 未成功返回错误
3. 删除：删除选择的课程，智能返回结果

## 进阶要求



1. 查询增强，根据描述返回用户最为感兴趣的课程
   1. 例如：用户喜欢体育，羽毛球等放在前面
2. 选择增强：当用户在选课和删除时提供的课程不准确时，智能提供可能用户想提的课程
