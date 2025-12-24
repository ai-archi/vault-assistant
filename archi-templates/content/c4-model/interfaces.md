# {{containerName}} 接口定义

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: 1.0

## 概述

本文档定义 {{containerName}} 容器中所有组件的接口规范。

## 接口分类

### REST API

#### {{api1}}

**端点**: `{{endpoint1}}`  
**方法**: {{httpMethod1}}  
**认证**: {{authentication1}}

**请求参数**:

| 参数名 | 类型 | 必填 | 描述 |
|--------|------|------|------|
| {{param1}} | {{paramType1}} | {{required1}} | {{paramDescription1}} |
| {{param2}} | {{paramType2}} | {{required2}} | {{paramDescription2}} |

**响应格式**:

```json
{
  "{{responseField1}}": "{{responseValue1}}",
  "{{responseField2}}": "{{responseValue2}}"
}
```

**错误码**:

| 错误码 | 描述 |
|--------|------|
| {{errorCode1}} | {{errorDescription1}} |
| {{errorCode2}} | {{errorDescription2}} |

---

#### {{api2}}

**端点**: `{{endpoint2}}`  
**方法**: {{httpMethod2}}  
**认证**: {{authentication2}}

**请求参数**:

| 参数名 | 类型 | 必填 | 描述 |
|--------|------|------|------|
| {{param3}} | {{paramType3}} | {{required3}} | {{paramDescription3}} |

**响应格式**:

```json
{
  "{{responseField3}}": "{{responseValue3}}"
}
```

---

### 消息接口

#### {{messageInterface1}}

**消息类型**: {{messageType1}}  
**协议**: {{protocol1}}  
**队列/主题**: {{queueOrTopic1}}

**消息格式**:

```json
{
  "{{messageField1}}": "{{messageValue1}}",
  "{{messageField2}}": "{{messageValue2}}"
}
```

**处理逻辑**: {{processingLogic1}}

---

### 数据库接口

#### {{databaseInterface1}}

**数据库类型**: {{databaseType1}}  
**连接方式**: {{connectionMethod1}}

**主要表/集合**:

| 表/集合名 | 描述 |
|---------|------|
| {{table1}} | {{tableDescription1}} |
| {{table2}} | {{tableDescription2}} |

---

## 接口版本管理

| 接口 | 当前版本 | 历史版本 | 废弃计划 |
|------|---------|---------|---------|
| {{api1}} | {{currentVersion1}} | {{historyVersions1}} | {{deprecationPlan1}} |
| {{api2}} | {{currentVersion2}} | {{historyVersions2}} | {{deprecationPlan2}} |

## 接口安全

{{interfaceSecurityDescription}}

### 认证机制

{{authenticationMechanism}}

### 授权策略

{{authorizationStrategy}}

### 数据加密

{{dataEncryption}}

## 接口性能

| 接口 | 平均响应时间 | 最大并发 | SLA |
|------|------------|---------|-----|
| {{api1}} | {{avgResponseTime1}} | {{maxConcurrency1}} | {{sla1}} |
| {{api2}} | {{avgResponseTime2}} | {{maxConcurrency2}} | {{sla2}} |

## 相关文档

- [[components.md]] - 组件清单
- [[../02-container/container-list.md]] - 容器清单

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

