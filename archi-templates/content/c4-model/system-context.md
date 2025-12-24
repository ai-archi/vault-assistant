# {{systemName}} 系统上下文图

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: 1.0

## 概述

系统上下文图（System Context Diagram）是 C4 模型的第一层，用于展示系统与外部用户和系统之间的高层次交互关系。

## 系统边界

{{systemBoundaryDescription}}

## 系统用户

| 用户类型 | 描述 | 交互方式 |
|---------|------|---------|
| {{userType1}} | {{userDescription1}} | {{interactionMethod1}} |
| {{userType2}} | {{userDescription2}} | {{interactionMethod2}} |

## 外部系统

| 系统名称 | 类型 | 描述 | 交互方式 |
|---------|------|------|---------|
| {{externalSystem1}} | {{systemType1}} | {{systemDescription1}} | {{interactionMethod1}} |
| {{externalSystem2}} | {{systemType2}} | {{systemDescription2}} | {{interactionMethod2}} |

## 系统上下文图

### Mermaid 格式

```mermaid
C4Context
    title {{systemName}} 系统上下文图
    
    Person(user, "{{userLabel}}", "{{userDescription}}")
    System(system, "{{systemName}}", "{{systemDescription}}")
    System_Ext({{externalSystem1}}, "{{externalSystem1Label}}", "{{externalSystem1Description}}")
    System_Ext({{externalSystem2}}, "{{externalSystem2Label}}", "{{externalSystem2Description}}")
    
    Rel(user, system, "{{userInteraction}}")
    Rel(system, {{externalSystem1}}, "{{systemInteraction1}}")
    Rel(system, {{externalSystem2}}, "{{systemInteraction2}}")
```

### Mermaid 文件

参考 [[system-context.mmd]]

## 关键交互

1. **{{interaction1}}**: {{interactionDescription1}}
2. **{{interaction2}}**: {{interactionDescription2}}
3. **{{interaction3}}**: {{interactionDescription3}}

## 非功能性需求

- **性能**: {{performanceRequirement}}
- **可用性**: {{availabilityRequirement}}
- **安全性**: {{securityRequirement}}

## 相关文档

- [[stakeholders.md]] - 利益相关者分析
- [[../02-container/container-diagram.md]] - 容器图

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

