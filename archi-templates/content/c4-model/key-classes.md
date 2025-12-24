# {{containerName}} 关键类说明

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: 1.0

## 概述

本文档说明 {{containerName}} 容器中的关键类和它们的设计意图。

## 关键类列表

### {{class1}}

**包**: `{{package1}}`  
**类型**: {{classType1}}  
**职责**: {{class1Responsibility}}

#### 设计意图

{{class1DesignIntent}}

#### 主要方法

| 方法名 | 返回类型 | 描述 |
|--------|---------|------|
| {{method1}} | {{returnType1}} | {{methodDescription1}} |
| {{method2}} | {{returnType2}} | {{methodDescription2}} |

#### 依赖关系

- **依赖**: {{class1Dependencies}}
- **被依赖**: {{class1Dependents}}

#### 设计模式

{{class1DesignPatterns}}

---

### {{class2}}

**包**: `{{package2}}`  
**类型**: {{classType2}}  
**职责**: {{class2Responsibility}}

#### 设计意图

{{class2DesignIntent}}

#### 主要方法

| 方法名 | 返回类型 | 描述 |
|--------|---------|------|
| {{method3}} | {{returnType3}} | {{methodDescription3}} |
| {{method4}} | {{returnType4}} | {{methodDescription4}} |

#### 依赖关系

- **依赖**: {{class2Dependencies}}
- **被依赖**: {{class2Dependents}}

#### 设计模式

{{class2DesignPatterns}}

---

## 类关系图

```mermaid
classDiagram
    class {{class1}} {
        +{{method1}}()
        +{{method2}}()
    }
    class {{class2}} {
        +{{method3}}()
        +{{method4}}()
    }
    class {{class3}} {
        +{{method5}}()
    }
    
    {{class1}} --> {{class2}}
    {{class2}} --> {{class3}}
```

## 设计原则应用

{{designPrinciplesApplication}}

## 相关文档

- [[components.md]] - 组件清单
- [[package-structure.md]] - 包结构说明
- [[sequence.md]] - 序列图

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

