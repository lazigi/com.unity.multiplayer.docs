---  
id: Unity.Networking.Transport.NetworkPipelineStageCollection  
title: Unity.Networking.Transport.NetworkPipelineStageCollection  
---

<div class="markdown level0 summary">

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

Object.Equals(Object)

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetHashCode()

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

    public static class NetworkPipelineStageCollection

## Methods 

### GetStageId(Type)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public static NetworkPipelineStageId GetStageId(Type stageType)

#### Parameters

| Type        | Name      | Description |
|-------------|-----------|-------------|
| System.Type | stageType |             |

#### Returns

| Type                   | Description |
|------------------------|-------------|
| NetworkPipelineStageId |             |

### RegisterPipelineStage(INetworkPipelineStage)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public static void RegisterPipelineStage(INetworkPipelineStage stage)

#### Parameters

| Type                  | Name  | Description |
|-----------------------|-------|-------------|
| INetworkPipelineStage | stage |             |
