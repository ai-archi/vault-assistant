# {{systemName}} 容器清单

**创建日期**: {{date}}  
**架构师**: {{architect}}  
**版本**: 1.0

## 概述

本文档提供系统中所有容器的详细清单，包括技术栈、职责、接口和部署信息。

## 容器列表

### {{container1}}

**技术**: {{technology1}}  
**类型**: {{containerType1}}  
**状态**: {{status1}}

#### 职责

{{container1Responsibilities}}

#### 技术栈

- **运行时**: {{runtime1}}
- **框架**: {{framework1}}
- **数据库**: {{database1}}
- **其他**: {{otherTech1}}

#### 接口

| 接口名称 | 类型 | 协议 | 描述 |
|---------|------|------|------|
| {{interface1}} | {{interfaceType1}} | {{protocol1}} | {{interfaceDescription1}} |
| {{interface2}} | {{interfaceType2}} | {{protocol2}} | {{interfaceDescription2}} |

#### 依赖关系

- **依赖**: {{dependencies1}}
- **被依赖**: {{dependents1}}

#### 部署信息

- **部署环境**: {{deploymentEnvironment1}}
- **实例数量**: {{instanceCount1}}
- **资源需求**: {{resourceRequirements1}}

---

### {{container2}}

**技术**: {{technology2}}  
**类型**: {{containerType2}}  
**状态**: {{status2}}

#### 职责

{{container2Responsibilities}}

#### 技术栈

- **运行时**: {{runtime2}}
- **框架**: {{framework2}}
- **数据库**: {{database2}}
- **其他**: {{otherTech2}}

#### 接口

| 接口名称 | 类型 | 协议 | 描述 |
|---------|------|------|------|
| {{interface3}} | {{interfaceType3}} | {{protocol3}} | {{interfaceDescription3}} |

#### 依赖关系

- **依赖**: {{dependencies2}}
- **被依赖**: {{dependents2}}

#### 部署信息

- **部署环境**: {{deploymentEnvironment2}}
- **实例数量**: {{instanceCount2}}
- **资源需求**: {{resourceRequirements2}}

---

## 容器关系矩阵

| 容器 | {{container1}} | {{container2}} | {{container3}} |
|------|---------------|---------------|---------------|
| {{container1}} | - | {{relationship1}} | {{relationship2}} |
| {{container2}} | {{relationship3}} | - | {{relationship4}} |
| {{container3}} | {{relationship5}} | {{relationship6}} | - |

## 技术栈汇总

| 技术类型 | 使用的容器 | 版本 |
|---------|-----------|------|
| {{techType1}} | {{containersUsingTech1}} | {{version1}} |
| {{techType2}} | {{containersUsingTech2}} | {{version2}} |

## 相关文档

- [[container-diagram.md]] - 容器图
- [[deployment-view.md]] - 部署视图
- [[../03-component/README.md]] - 组件图

## 变更记录

| 日期 | 版本 | 变更内容 | 变更人 |
|------|------|----------|--------|
| {{date}} | 1.0 | 初始版本 | {{architect}} |

