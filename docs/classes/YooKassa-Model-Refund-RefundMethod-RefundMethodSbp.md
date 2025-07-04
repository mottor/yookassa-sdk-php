# [YooKassa API SDK](../home.md)

# Class: \YooKassa\Model\Refund\RefundMethod\RefundMethodSbp
### Namespace: [\YooKassa\Model\Refund\RefundMethod](../namespaces/yookassa-model-refund-refundmethod.md)
---
**Summary:**

Класс, представляющий модель RefundMethodSbp.

**Description:**

Возврат через СБП (Система быстрых платежей ЦБ РФ).

---
### Constants
* No constants found

---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [$sbp_operation_id](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md#property_sbp_operation_id) |  | Идентификатор операции в СБП (НСПК). |
| public | [$sbpOperationId](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md#property_sbpOperationId) |  | Идентификатор операции в СБП (НСПК). |
| public | [$type](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md#property_type) |  | Код метода возврата |
| protected | [$_type](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md#property__type) |  | Код метода возврата. |

---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md#method___construct) |  |  |
| public | [__get()](../classes/YooKassa-Common-AbstractObject.md#method___get) |  | Возвращает значение свойства. |
| public | [__isset()](../classes/YooKassa-Common-AbstractObject.md#method___isset) |  | Проверяет наличие свойства. |
| public | [__set()](../classes/YooKassa-Common-AbstractObject.md#method___set) |  | Устанавливает значение свойства. |
| public | [__unset()](../classes/YooKassa-Common-AbstractObject.md#method___unset) |  | Удаляет свойство. |
| public | [fromArray()](../classes/YooKassa-Common-AbstractObject.md#method_fromArray) |  | Устанавливает значения свойств текущего объекта из массива. |
| public | [getSbpOperationId()](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md#method_getSbpOperationId) |  | Возвращает sbp_operation_id. |
| public | [getType()](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md#method_getType) |  | Возвращает тип метода возврата. |
| public | [getValidator()](../classes/YooKassa-Common-AbstractObject.md#method_getValidator) |  |  |
| public | [jsonSerialize()](../classes/YooKassa-Common-AbstractObject.md#method_jsonSerialize) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации. |
| public | [offsetExists()](../classes/YooKassa-Common-AbstractObject.md#method_offsetExists) |  | Проверяет наличие свойства. |
| public | [offsetGet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetGet) |  | Возвращает значение свойства. |
| public | [offsetSet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetSet) |  | Устанавливает значение свойства. |
| public | [offsetUnset()](../classes/YooKassa-Common-AbstractObject.md#method_offsetUnset) |  | Удаляет свойство. |
| public | [setSbpOperationId()](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md#method_setSbpOperationId) |  | Устанавливает sbp_operation_id. |
| public | [setType()](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md#method_setType) |  | Устанавливает тип метода возврата. |
| public | [toArray()](../classes/YooKassa-Common-AbstractObject.md#method_toArray) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации Является алиасом метода AbstractObject::jsonSerialize(). |
| protected | [getUnknownProperties()](../classes/YooKassa-Common-AbstractObject.md#method_getUnknownProperties) |  | Возвращает массив свойств которые не существуют, но были заданы у объекта. |
| protected | [validatePropertyValue()](../classes/YooKassa-Common-AbstractObject.md#method_validatePropertyValue) |  |  |

---
### Details
* File: [lib/Model/Refund/RefundMethod/RefundMethodSbp.php](../../lib/Model/Refund/RefundMethod/RefundMethodSbp.php)
* Package: YooKassa\Model
* Class Hierarchy:  
  * [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)
  * [\YooKassa\Model\Refund\RefundMethod\AbstractRefundMethod](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md)
  * \YooKassa\Model\Refund\RefundMethod\RefundMethodSbp

* See Also:
  * [](https://yookassa.ru/developers/api)

---
### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| category |  | Class |
| author |  | cms@yoomoney.ru |

---
## Properties
<a name="property_sbp_operation_id"></a>
#### public $sbp_operation_id : string|null
---
***Description***

Идентификатор операции в СБП (НСПК).

**Type:** <a href="../string|null"><abbr title="string|null">string|null</abbr></a>

**Details:**


<a name="property_sbpOperationId"></a>
#### public $sbpOperationId : string|null
---
***Description***

Идентификатор операции в СБП (НСПК).

**Type:** <a href="../string|null"><abbr title="string|null">string|null</abbr></a>

**Details:**


<a name="property_type"></a>
#### public $type : string
---
***Description***

Код метода возврата

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\AbstractRefundMethod](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md)


<a name="property__type"></a>
#### protected $_type : ?string
---
**Summary**

Код метода возврата.

**Type:** <a href="../?string"><abbr title="?string">?string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\AbstractRefundMethod](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct(?array $data = []) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\RefundMethodSbp](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">?array</code> | data  |  |

**Returns:** mixed - 


<a name="method___get" class="anchor"></a>
#### public __get() : mixed

```php
public __get(string $propertyName) : mixed
```

**Summary**

Возвращает значение свойства.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя свойства |

**Returns:** mixed - Значение свойства


<a name="method___isset" class="anchor"></a>
#### public __isset() : bool

```php
public __isset(string $propertyName) : bool
```

**Summary**

Проверяет наличие свойства.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя проверяемого свойства |

**Returns:** bool - True если свойство имеется, false если нет


<a name="method___set" class="anchor"></a>
#### public __set() : void

```php
public __set(string $propertyName, mixed $value) : void
```

**Summary**

Устанавливает значение свойства.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя свойства |
| <code lang="php">mixed</code> | value  | Значение свойства |

**Returns:** void - 


<a name="method___unset" class="anchor"></a>
#### public __unset() : void

```php
public __unset(string $propertyName) : void
```

**Summary**

Удаляет свойство.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  | Имя удаляемого свойства |

**Returns:** void - 


<a name="method_fromArray" class="anchor"></a>
#### public fromArray() : void

```php
public fromArray(array|\Traversable $sourceArray) : void
```

**Summary**

Устанавливает значения свойств текущего объекта из массива.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">array OR \Traversable</code> | sourceArray  | Ассоциативный массив с настройками |

**Returns:** void - 


<a name="method_getSbpOperationId" class="anchor"></a>
#### public getSbpOperationId() : string|null

```php
public getSbpOperationId() : string|null
```

**Summary**

Возвращает sbp_operation_id.

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\RefundMethodSbp](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md)

**Returns:** string|null - 


<a name="method_getType" class="anchor"></a>
#### public getType() : string|null

```php
public getType() : string|null
```

**Summary**

Возвращает тип метода возврата.

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\AbstractRefundMethod](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md)

**Returns:** string|null - Тип метода возврата


<a name="method_getValidator" class="anchor"></a>
#### public getValidator() : \YooKassa\Validator\Validator

```php
public getValidator() : \YooKassa\Validator\Validator
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** \YooKassa\Validator\Validator - 


<a name="method_jsonSerialize" class="anchor"></a>
#### public jsonSerialize() : array

```php
public jsonSerialize() : array
```

**Summary**

Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** array - Ассоциативный массив со свойствами текущего объекта


<a name="method_offsetExists" class="anchor"></a>
#### public offsetExists() : bool

```php
public offsetExists(string $offset) : bool
```

**Summary**

Проверяет наличие свойства.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | offset  | Имя проверяемого свойства |

**Returns:** bool - True если свойство имеется, false если нет


<a name="method_offsetGet" class="anchor"></a>
#### public offsetGet() : mixed

```php
public offsetGet(string $offset) : mixed
```

**Summary**

Возвращает значение свойства.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | offset  | Имя свойства |

**Returns:** mixed - Значение свойства


<a name="method_offsetSet" class="anchor"></a>
#### public offsetSet() : void

```php
public offsetSet(string $offset, mixed $value) : void
```

**Summary**

Устанавливает значение свойства.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | offset  | Имя свойства |
| <code lang="php">mixed</code> | value  | Значение свойства |

**Returns:** void - 


<a name="method_offsetUnset" class="anchor"></a>
#### public offsetUnset() : void

```php
public offsetUnset(string $offset) : void
```

**Summary**

Удаляет свойство.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | offset  | Имя удаляемого свойства |

**Returns:** void - 


<a name="method_setSbpOperationId" class="anchor"></a>
#### public setSbpOperationId() : self

```php
public setSbpOperationId(string|null $sbp_operation_id = null) : self
```

**Summary**

Устанавливает sbp_operation_id.

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\RefundMethodSbp](../classes/YooKassa-Model-Refund-RefundMethod-RefundMethodSbp.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string OR null</code> | sbp_operation_id  | Идентификатор операции в СБП (НСПК). |

**Returns:** self - 


<a name="method_setType" class="anchor"></a>
#### public setType() : self

```php
public setType(string|null $type = null) : self
```

**Summary**

Устанавливает тип метода возврата.

**Details:**
* Inherited From: [\YooKassa\Model\Refund\RefundMethod\AbstractRefundMethod](../classes/YooKassa-Model-Refund-RefundMethod-AbstractRefundMethod.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string OR null</code> | type  | Тип метода возврата |

**Returns:** self - 


<a name="method_toArray" class="anchor"></a>
#### public toArray() : array

```php
public toArray() : array
```

**Summary**

Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации
Является алиасом метода AbstractObject::jsonSerialize().

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** array - Ассоциативный массив со свойствами текущего объекта


<a name="method_getUnknownProperties" class="anchor"></a>
#### protected getUnknownProperties() : array

```php
protected getUnknownProperties() : array
```

**Summary**

Возвращает массив свойств которые не существуют, но были заданы у объекта.

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

**Returns:** array - Ассоциативный массив с не существующими у текущего объекта свойствами


<a name="method_validatePropertyValue" class="anchor"></a>
#### protected validatePropertyValue() : mixed

```php
protected validatePropertyValue(string $propertyName, mixed $propertyValue) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string</code> | propertyName  |  |
| <code lang="php">mixed</code> | propertyValue  |  |

**Returns:** mixed - 



---

### Top Namespaces

* [\YooKassa](../namespaces/yookassa.md)

---

### Reports
* [Errors - 0](../reports/errors.md)
* [Markers - 0](../reports/markers.md)
* [Deprecated - 33](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2025-07-01 using [phpDocumentor](http://www.phpdoc.org/)

&copy; 2025 YooMoney