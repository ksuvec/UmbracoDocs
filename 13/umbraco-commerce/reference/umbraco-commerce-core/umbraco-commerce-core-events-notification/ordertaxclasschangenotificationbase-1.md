---
title: OrderTaxClassChangeNotificationBase<TEntity>
description: API reference for OrderTaxClassChangeNotificationBase<TEntity> in Umbraco Commerce
---
## OrderTaxClassChangeNotificationBase&lt;TEntity&gt;

```csharp
public abstract class OrderTaxClassChangeNotificationBase<TEntity> : 
    OrderNotificationEventBase<TEntity>
    where TEntity : OrderReadOnly
```

**Inheritance**

* Class [OrderNotificationEventBase&lt;TOrder&gt;](ordernotificationeventbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderTaxClassChangeNotificationBase&lt;TEntity&gt;

```csharp
public OrderTaxClassChangeNotificationBase(TEntity order, ChangingValue<Guid?> taxClassId)
```


### Properties

#### TaxClassId

```csharp
public ChangingValue<Guid?> TaxClassId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->