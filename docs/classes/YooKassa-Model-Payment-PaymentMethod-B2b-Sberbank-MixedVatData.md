# [YooKassa API SDK](../home.md)

# Class: \YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\MixedVatData
### Namespace: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank](../namespaces/yookassa-model-payment-paymentmethod-b2b-sberbank.md)
---
**Summary:**

Класс, представляющий модель MixedVatData.

**Description:**

Данные об НДС, если создается платеж на несколько товаров или услуг с разными ставками НДС (в параметре `type` передано значение ~`mixed`).

---
### Constants
* No constants found

---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [$amount](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md#property_amount) |  | Сумма НДС |
| public | [$type](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md#property_type) |  | Способ расчёта НДС |
| protected | [$_type](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md#property__type) |  |  |

---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md#method___construct) |  |  |
| public | [__get()](../classes/YooKassa-Common-AbstractObject.md#method___get) |  | Возвращает значение свойства. |
| public | [__isset()](../classes/YooKassa-Common-AbstractObject.md#method___isset) |  | Проверяет наличие свойства. |
| public | [__set()](../classes/YooKassa-Common-AbstractObject.md#method___set) |  | Устанавливает значение свойства. |
| public | [__unset()](../classes/YooKassa-Common-AbstractObject.md#method___unset) |  | Удаляет свойство. |
| public | [fromArray()](../classes/YooKassa-Common-AbstractObject.md#method_fromArray) |  | Устанавливает значения свойств текущего объекта из массива. |
| public | [getAmount()](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md#method_getAmount) |  | Возвращает сумму НДС |
| public | [getType()](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md#method_getType) |  | Возвращает способ расчёта НДС |
| public | [getValidator()](../classes/YooKassa-Common-AbstractObject.md#method_getValidator) |  |  |
| public | [jsonSerialize()](../classes/YooKassa-Common-AbstractObject.md#method_jsonSerialize) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации. |
| public | [offsetExists()](../classes/YooKassa-Common-AbstractObject.md#method_offsetExists) |  | Проверяет наличие свойства. |
| public | [offsetGet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetGet) |  | Возвращает значение свойства. |
| public | [offsetSet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetSet) |  | Устанавливает значение свойства. |
| public | [offsetUnset()](../classes/YooKassa-Common-AbstractObject.md#method_offsetUnset) |  | Удаляет свойство. |
| public | [setAmount()](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md#method_setAmount) |  | Устанавливает сумму НДС |
| public | [setType()](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md#method_setType) |  | Устанавливает способ расчёта НДС |
| public | [toArray()](../classes/YooKassa-Common-AbstractObject.md#method_toArray) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации Является алиасом метода AbstractObject::jsonSerialize(). |
| protected | [getUnknownProperties()](../classes/YooKassa-Common-AbstractObject.md#method_getUnknownProperties) |  | Возвращает массив свойств которые не существуют, но были заданы у объекта. |
| protected | [validatePropertyValue()](../classes/YooKassa-Common-AbstractObject.md#method_validatePropertyValue) |  |  |

---
### Details
* File: [lib/Model/Payment/PaymentMethod/B2b/Sberbank/MixedVatData.php](../../lib/Model/Payment/PaymentMethod/B2b/Sberbank/MixedVatData.php)
* Package: YooKassa\Model
* Class Hierarchy:  
  * [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)
  * [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\AbstractVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md)
  * \YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\MixedVatData

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
<a name="property_amount"></a>
#### public $amount : \YooKassa\Model\AmountInterface
---
***Description***

Сумма НДС

**Type:** <a href="../classes/YooKassa-Model-AmountInterface.html"><abbr title="\YooKassa\Model\AmountInterface">AmountInterface</abbr></a>

**Details:**


<a name="property_type"></a>
#### public $type : string
---
***Description***

Способ расчёта НДС

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\AbstractVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md)


<a name="property__type"></a>
#### protected $_type : ?string
---
**Type:** <a href="../?string"><abbr title="?string">?string</abbr></a>
Способ расчёта НДС
**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\AbstractVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct(?array $data = []) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\MixedVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md)

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


<a name="method_getAmount" class="anchor"></a>
#### public getAmount() : \YooKassa\Model\AmountInterface|null

```php
public getAmount() : \YooKassa\Model\AmountInterface|null
```

**Summary**

Возвращает сумму НДС

**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\MixedVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md)

**Returns:** \YooKassa\Model\AmountInterface|null - Сумма НДС


<a name="method_getType" class="anchor"></a>
#### public getType() : string|null

```php
public getType() : string|null
```

**Summary**

Возвращает способ расчёта НДС

**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\AbstractVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md)

**Returns:** string|null - Способ расчёта НДС


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


<a name="method_setAmount" class="anchor"></a>
#### public setAmount() : self

```php
public setAmount(null|\YooKassa\Model\AmountInterface|array $amount) : self
```

**Summary**

Устанавливает сумму НДС

**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\MixedVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-MixedVatData.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">null OR \YooKassa\Model\AmountInterface OR array</code> | amount  | Сумма НДС |

**Returns:** self - 


<a name="method_setType" class="anchor"></a>
#### public setType() : self

```php
public setType(string|null $type) : self
```

**Summary**

Устанавливает способ расчёта НДС

**Details:**
* Inherited From: [\YooKassa\Model\Payment\PaymentMethod\B2b\Sberbank\AbstractVatData](../classes/YooKassa-Model-Payment-PaymentMethod-B2b-Sberbank-AbstractVatData.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string OR null</code> | type  | Способ расчёта НДС |

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