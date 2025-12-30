# {{relationshipName}} 关系定义

**创建日期**: {{date}}  
**定义者**: {{author}}  
**版本**: {{version}}  
**状态**: {{status}}

## 概述

本文档定义了架构元模型中的 **{{relationshipName}}** 关系类型，用于描述架构元素之间的连接和交互。

## 关系定义

### 名称

**{{relationshipName}}**

### 定义

{{relationshipDefinition}}

### 关系类型

{{relationshipType}}

### 方向性

- [ ] 有向关系
- [ ] 无向关系
- [ ] 双向关系

## 关系属性

| 属性名称       | 类型      | 必填          | 说明             | 示例         |
| -------------- | --------- | ------------- | ---------------- | ------------ |
| {{attribute1}} | {{type1}} | {{required1}} | {{description1}} | {{example1}} |
| {{attribute2}} | {{type2}} | {{required2}} | {{description2}} | {{example2}} |

## 源元素类型

可以建立此关系的源元素类型：

- {{sourceElementType1}}
- {{sourceElementType2}}
- {{sourceElementType3}}

## 目标元素类型

可以建立此关系的目标元素类型：

- {{targetElementType1}}
- {{targetElementType2}}
- {{targetElementType3}}

## 关系语义

### 语义说明

{{semanticDescription}}

### 传递性

- [ ] 可传递
- [ ] 不可传递

### 对称性

- [ ] 对称关系
- [ ] 非对称关系

## 使用场景

### 场景 1: {{scenario1}}

{{scenario1Description}}

**示例**:

```
{{sourceElement}} --{{relationshipName}}--> {{targetElement}}
```

### 场景 2: {{scenario2}}

{{scenario2Description}}

## 表示法

### 图形表示

```mermaid
graph LR
    A[源元素] -->|{{relationshipName}}| B[目标元素]

    style A fill:#4a90e2,color:#fff
    style B fill:#50c878,color:#fff
```

### 文本表示

{{textualNotation}}

## 示例

### 示例 1: {{example1Name}}

{{example1Description}}

```mermaid
graph TB
    A[{{example1Source}}] -->|{{relationshipName}}| B[{{example1Target}}]
```

### 示例 2: {{example2Name}}

{{example2Description}}

## 约束规则

{{constraintRules}}

## 与其他关系的区别

| 对比关系                  | 区别点          | 说明             |
| ------------------------- | --------------- | ---------------- |
| {{contrastRelationship1}} | {{difference1}} | {{explanation1}} |
| {{contrastRelationship2}} | {{difference2}} | {{explanation2}} |

## 相关文档

- [[架构元模型概览]]
- [[概念定义]]
- [[表示法指南]]

## 变更记录

| 日期     | 版本 | 变更内容 | 变更人     |
| -------- | ---- | -------- | ---------- |
| {{date}} | 1.0  | 初始版本 | {{author}} |
