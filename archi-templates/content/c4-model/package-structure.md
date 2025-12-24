# {{containerName}} 包结构说明

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: 1.0

## 概述

本文档说明 {{containerName}} 容器的包/模块结构。

## 包结构

```
{{packageRoot}}/
├── {{package1}}/
│   ├── {{subpackage1}}/
│   │   └── {{class1}}.java
│   └── {{subpackage2}}/
│       └── {{class2}}.java
├── {{package2}}/
│   ├── {{subpackage3}}/
│   └── {{subpackage4}}/
└── {{package3}}/
    └── {{subpackage5}}/
```

## 包说明

### {{package1}}

**职责**: {{package1Responsibility}}  
**包含组件**: {{package1Components}}

#### 主要类

| 类名 | 职责 | 依赖 |
|------|------|------|
| {{class1}} | {{class1Responsibility}} | {{class1Dependencies}} |
| {{class2}} | {{class2Responsibility}} | {{class2Dependencies}} |

---

### {{package2}}

**职责**: {{package2Responsibility}}  
**包含组件**: {{package2Components}}

#### 主要类

| 类名 | 职责 | 依赖 |
|------|------|------|
| {{class3}} | {{class3Responsibility}} | {{class3Dependencies}} |

---

## 包依赖关系

{{packageDependencyDescription}}

### 依赖图

```mermaid
graph TD
    {{package1}} --> {{package2}}
    {{package1}} --> {{package3}}
    {{package2}} --> {{package3}}
```

## 分层架构

### 表示层 (Presentation Layer)

{{presentationLayerPackages}}

### 业务逻辑层 (Business Logic Layer)

{{businessLogicLayerPackages}}

### 数据访问层 (Data Access Layer)

{{dataAccessLayerPackages}}

### 基础设施层 (Infrastructure Layer)

{{infrastructureLayerPackages}}

## 命名规范

{{namingConventions}}

## 相关文档

- [[components.md]] - 组件清单
- [[key-classes.md]] - 关键类说明

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

