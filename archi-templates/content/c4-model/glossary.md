# {{systemName}} 架构术语表

**创建日期**: {{date}}  
**维护者**: {{maintainer}}  
**版本**: 1.0

## 概述

本文档定义 {{systemName}} 架构文档中使用的术语和概念。

## 术语定义

### A

#### {{term1}}

**定义**: {{term1Definition}}  
**上下文**: {{term1Context}}  
**相关术语**: {{term1RelatedTerms}}

---

### B

#### {{term2}}

**定义**: {{term2Definition}}  
**上下文**: {{term2Context}}  
**相关术语**: {{term2RelatedTerms}}

---

### C

#### 容器 (Container)

**定义**: C4模型中的容器是一个可独立部署/执行的可执行单元或进程，例如Web应用、移动应用、数据库等。  
**上下文**: C4模型 Level 2  
**相关术语**: 组件、系统

#### 组件 (Component)

**定义**: C4模型中的组件是容器内的逻辑单元，通常对应代码中的模块、类或包。  
**上下文**: C4模型 Level 3  
**相关术语**: 容器、类

---

### D

#### {{term3}}

**定义**: {{term3Definition}}  
**上下文**: {{term3Context}}  
**相关术语**: {{term3RelatedTerms}}

---

## C4模型术语

### 系统上下文 (System Context)

**定义**: C4模型的第一层，展示系统与外部用户和系统之间的高层次交互关系。  
**相关文档**: [[../01-context/system-context.md]]

### 容器图 (Container Diagram)

**定义**: C4模型的第二层，展示系统内部的高层次技术构建块（容器）以及它们之间的关系。  
**相关文档**: [[../02-container/container-diagram.md]]

### 组件图 (Component Diagram)

**定义**: C4模型的第三层，展示容器内部的组件以及它们之间的关系。  
**相关文档**: [[../03-component/README.md]]

## 架构模式术语

### {{pattern1}}

**定义**: {{pattern1Definition}}  
**使用场景**: {{pattern1UseCase}}  
**相关文档**: {{pattern1RelatedDocs}}

---

## 技术术语

### {{techTerm1}}

**定义**: {{techTerm1Definition}}  
**上下文**: {{techTerm1Context}}

---

## 缩写词表

| 缩写 | 全称 | 中文 | 说明 |
|------|------|------|------|
| ADR | Architecture Decision Record | 架构决策记录 | 记录架构决策的文档 |
| API | Application Programming Interface | 应用程序编程接口 | 应用程序之间的接口 |
| C4 | Context, Containers, Components, Code | C4模型 | 软件架构模型 |
| RBAC | Role-Based Access Control | 基于角色的访问控制 | 访问控制模型 |
| RTO | Recovery Time Objective | 恢复时间目标 | 灾难恢复指标 |
| RPO | Recovery Point Objective | 恢复点目标 | 灾难恢复指标 |

## 相关文档

- [[../01-context/system-context.md]] - 系统上下文图
- [[../02-container/container-diagram.md]] - 容器图
- [[../03-component/README.md]] - 组件图

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{maintainer}} |

