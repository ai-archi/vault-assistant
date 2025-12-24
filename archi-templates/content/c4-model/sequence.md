# {{containerName}} 关键序列图

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: 1.0

## 概述

本文档展示 {{containerName}} 容器中关键业务流程的序列图。

## 序列图列表

### {{scenario1}}

**场景描述**: {{scenario1Description}}

#### 序列图

```mermaid
sequenceDiagram
    participant {{actor1}} as {{actor1Label}}
    participant {{component1}} as {{component1Label}}
    participant {{component2}} as {{component2Label}}
    participant {{component3}} as {{component3Label}}
    
    {{actor1}}->>{{component1}}: {{interaction1}}
    activate {{component1}}
    {{component1}}->>{{component2}}: {{interaction2}}
    activate {{component2}}
    {{component2}}->>{{component3}}: {{interaction3}}
    activate {{component3}}
    {{component3}}-->>{{component2}}: {{response1}}
    deactivate {{component3}}
    {{component2}}-->>{{component1}}: {{response2}}
    deactivate {{component2}}
    {{component1}}-->>{{actor1}}: {{response3}}
    deactivate {{component1}}
```

#### PlantUML 格式

```plantuml
@startuml
{{actor1}} -> {{component1}}: {{interaction1}}
activate {{component1}}
{{component1}} -> {{component2}}: {{interaction2}}
activate {{component2}}
{{component2}} -> {{component3}}: {{interaction3}}
activate {{component3}}
{{component3}} --> {{component2}}: {{response1}}
deactivate {{component3}}
{{component2}} --> {{component1}}: {{response2}}
deactivate {{component2}}
{{component1}} --> {{actor1}}: {{response3}}
deactivate {{component1}}
@enduml
```

#### 说明

{{scenario1Explanation}}

---

### {{scenario2}}

**场景描述**: {{scenario2Description}}

#### 序列图

```mermaid
sequenceDiagram
    participant {{actor2}} as {{actor2Label}}
    participant {{component4}} as {{component4Label}}
    participant {{component5}} as {{component5Label}}
    
    {{actor2}}->>{{component4}}: {{interaction4}}
    activate {{component4}}
    {{component4}}->>{{component5}}: {{interaction5}}
    activate {{component5}}
    {{component5}}-->>{{component4}}: {{response4}}
    deactivate {{component5}}
    {{component4}}-->>{{actor2}}: {{response5}}
    deactivate {{component4}}
```

#### 说明

{{scenario2Explanation}}

---

## 异常处理流程

### {{exceptionScenario1}}

**异常类型**: {{exceptionType1}}  
**处理方式**: {{exceptionHandling1}}

```mermaid
sequenceDiagram
    participant {{actor3}} as {{actor3Label}}
    participant {{component6}} as {{component6Label}}
    participant {{errorHandler}} as {{errorHandlerLabel}}
    
    {{actor3}}->>{{component6}}: {{interaction6}}
    activate {{component6}}
    {{component6}}->>{{errorHandler}}: {{errorOccurred}}
    activate {{errorHandler}}
    {{errorHandler}}-->>{{component6}}: {{errorResponse}}
    deactivate {{errorHandler}}
    {{component6}}-->>{{actor3}}: {{errorMessage}}
    deactivate {{component6}}
```

## 相关文档

- [[components.md]] - 组件清单
- [[interfaces.md]] - 接口定义
- [[key-classes.md]] - 关键类说明

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

