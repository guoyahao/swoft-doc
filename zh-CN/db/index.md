# 数据库
数据库操作支持基础查询和高级查询两种方式，为了方便简单，提供了统一语法操作数据库。

## 基础查询

基础查询，实现了类似ActiveRecord操作方式，方便简单快捷，但是不是支持事务。

## 高级查询

高级查询，采用Data Mapper 设计，支持事务功能，提供更加强大的功能操作数据库。

## 查询器

查询器是一套封装面向对象的方法，来实现SQL拼装和操作。

## SQL语句
获取最后执行SQL语句，调用get_last_sql()全局函数。
