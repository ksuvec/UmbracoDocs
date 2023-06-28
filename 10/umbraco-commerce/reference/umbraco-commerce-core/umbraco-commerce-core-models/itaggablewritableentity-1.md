---
title: ITaggableWritableEntity<TEntity>
description: API reference for ITaggableWritableEntity<TEntity> in Umbraco Commerce
---
## ITaggableWritableEntity&lt;TEntity&gt;

```csharp
public interface ITaggableWritableEntity<TEntity>
```

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Methods

#### AddTag

```csharp
public TEntity AddTag(string tag)
```


---

#### AddTags

```csharp
public TEntity AddTags(IEnumerable<string> tags)
```


---

#### ClearTags

```csharp
public TEntity ClearTags()
```


---

#### RemoveTag

```csharp
public TEntity RemoveTag(string tag)
```


---

#### RemoveTags

```csharp
public TEntity RemoveTags(IEnumerable<string> tags)
```


---

#### SetTags

```csharp
public TEntity SetTags(IEnumerable<string> tags, SetBehavior setBehavior = SetBehavior.Replace)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->