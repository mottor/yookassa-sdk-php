# [YooKassa API SDK](../home.md)

# Class: \YooKassa\Model\Payment\Confirmation\ConfirmationRedirect
### Namespace: [\YooKassa\Model\Payment\Confirmation](../namespaces/yookassa-model-payment-confirmation.md)
---
**Summary:**

Класс, представляющий модель ConfirmationRedirect.

**Description:**

Сценарий, при котором необходимо отправить плательщика на веб-страницу ЮKassa или партнера для
подтверждения платежа.

---
### Constants
* No constants found

---
### Properties
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [$confirmation_url](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#property_confirmation_url) |  | URL на который необходимо перенаправить плательщика для подтверждения оплаты |
| public | [$confirmationUrl](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#property_confirmationUrl) |  | URL на который необходимо перенаправить плательщика для подтверждения оплаты |
| public | [$enforce](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#property_enforce) |  | Требование принудительного подтверждения платежа покупателем, требование 3-D Secure для оплаты банковскими картами. По умолчанию определяется политикой платежной системы |
| public | [$return_url](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#property_return_url) |  | URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера |
| public | [$returnUrl](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#property_returnUrl) |  | URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера |
| public | [$type](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#property_type) |  | Тип подтверждения платежа |
| protected | [$_type](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#property__type) |  | Тип подтверждения платежа. |

---
### Methods
| Visibility | Name | Flag | Summary |
| ----------:| ---- | ---- | ------- |
| public | [__construct()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method___construct) |  |  |
| public | [__get()](../classes/YooKassa-Common-AbstractObject.md#method___get) |  | Возвращает значение свойства. |
| public | [__isset()](../classes/YooKassa-Common-AbstractObject.md#method___isset) |  | Проверяет наличие свойства. |
| public | [__set()](../classes/YooKassa-Common-AbstractObject.md#method___set) |  | Устанавливает значение свойства. |
| public | [__unset()](../classes/YooKassa-Common-AbstractObject.md#method___unset) |  | Удаляет свойство. |
| public | [fromArray()](../classes/YooKassa-Common-AbstractObject.md#method_fromArray) |  | Устанавливает значения свойств текущего объекта из массива. |
| public | [getConfirmationData()](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#method_getConfirmationData) |  |  |
| public | [getConfirmationToken()](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#method_getConfirmationToken) |  |  |
| public | [getConfirmationUrl()](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#method_getConfirmationUrl) |  |  |
| public | [getConfirmationUrl()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method_getConfirmationUrl) |  | Возвращает URL на который необходимо перенаправить плательщика для подтверждения оплаты |
| public | [getEnforce()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method_getEnforce) |  | Возвращает флаг принудительного подтверждения платежа покупателем |
| public | [getReturnUrl()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method_getReturnUrl) |  | Возвращает URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера |
| public | [getType()](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#method_getType) |  | Возвращает тип подтверждения платежа. |
| public | [getValidator()](../classes/YooKassa-Common-AbstractObject.md#method_getValidator) |  |  |
| public | [jsonSerialize()](../classes/YooKassa-Common-AbstractObject.md#method_jsonSerialize) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации. |
| public | [offsetExists()](../classes/YooKassa-Common-AbstractObject.md#method_offsetExists) |  | Проверяет наличие свойства. |
| public | [offsetGet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetGet) |  | Возвращает значение свойства. |
| public | [offsetSet()](../classes/YooKassa-Common-AbstractObject.md#method_offsetSet) |  | Устанавливает значение свойства. |
| public | [offsetUnset()](../classes/YooKassa-Common-AbstractObject.md#method_offsetUnset) |  | Удаляет свойство. |
| public | [setConfirmationUrl()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method_setConfirmationUrl) |  | Устанавливает URL на который необходимо перенаправить плательщика для подтверждения оплаты |
| public | [setEnforce()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method_setEnforce) |  | Устанавливает флаг принудительного подтверждения платежа покупателем |
| public | [setReturnUrl()](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md#method_setReturnUrl) |  | Устанавливает URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера |
| public | [setType()](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md#method_setType) |  | Устанавливает тип подтверждения платежа |
| public | [toArray()](../classes/YooKassa-Common-AbstractObject.md#method_toArray) |  | Возвращает ассоциативный массив со свойствами текущего объекта для его дальнейшей JSON сериализации Является алиасом метода AbstractObject::jsonSerialize(). |
| protected | [getUnknownProperties()](../classes/YooKassa-Common-AbstractObject.md#method_getUnknownProperties) |  | Возвращает массив свойств которые не существуют, но были заданы у объекта. |
| protected | [validatePropertyValue()](../classes/YooKassa-Common-AbstractObject.md#method_validatePropertyValue) |  |  |

---
### Details
* File: [lib/Model/Payment/Confirmation/ConfirmationRedirect.php](../../lib/Model/Payment/Confirmation/ConfirmationRedirect.php)
* Package: YooKassa\Model
* Class Hierarchy:  
  * [\YooKassa\Common\AbstractObject](../classes/YooKassa-Common-AbstractObject.md)
  * [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)
  * \YooKassa\Model\Payment\Confirmation\ConfirmationRedirect

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
<a name="property_confirmation_url"></a>
#### public $confirmation_url : string
---
***Description***

URL на который необходимо перенаправить плательщика для подтверждения оплаты

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_confirmationUrl"></a>
#### public $confirmationUrl : string
---
***Description***

URL на который необходимо перенаправить плательщика для подтверждения оплаты

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_enforce"></a>
#### public $enforce : bool
---
***Description***

Требование принудительного подтверждения платежа покупателем, требование 3-D Secure для
оплаты банковскими картами. По умолчанию определяется политикой платежной системы

**Type:** <a href="../bool"><abbr title="bool">bool</abbr></a>

**Details:**


<a name="property_return_url"></a>
#### public $return_url : string
---
***Description***

URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_returnUrl"></a>
#### public $returnUrl : string
---
***Description***

URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**


<a name="property_type"></a>
#### public $type : string
---
***Description***

Тип подтверждения платежа

**Type:** <a href="../string"><abbr title="string">string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)


<a name="property__type"></a>
#### protected $_type : ?string
---
**Summary**

Тип подтверждения платежа.

**Type:** <a href="../?string"><abbr title="?string">?string</abbr></a>

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() : mixed

```php
public __construct(?array $data = []) : mixed
```

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

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


<a name="method_getConfirmationData" class="anchor"></a>
#### public getConfirmationData() 

```php
public getConfirmationData() 
```

**Description**

Для ConfirmationQr

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)

**Returns:**  - 


<a name="method_getConfirmationToken" class="anchor"></a>
#### public getConfirmationToken() 

```php
public getConfirmationToken() 
```

**Description**

Для ConfirmationEmbedded

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)

**Returns:**  - 


<a name="method_getConfirmationUrl" class="anchor"></a>
#### public getConfirmationUrl() 

```php
public getConfirmationUrl() 
```

**Description**

Для ConfirmationRedirect

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)

**Returns:**  - 


<a name="method_getConfirmationUrl" class="anchor"></a>
#### public getConfirmationUrl() : string|null

```php
public getConfirmationUrl() : string|null
```

**Summary**

Возвращает URL на который необходимо перенаправить плательщика для подтверждения оплаты

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

**Returns:** string|null - URL на который необходимо перенаправить плательщика для подтверждения оплаты


<a name="method_getEnforce" class="anchor"></a>
#### public getEnforce() : bool

```php
public getEnforce() : bool
```

**Summary**

Возвращает флаг принудительного подтверждения платежа покупателем

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

**Returns:** bool - Требование принудительного подтверждения платежа покупателем, требование 3-D Secure для
оплаты банковскими картами. По умолчанию определяется политикой платежной системы.


<a name="method_getReturnUrl" class="anchor"></a>
#### public getReturnUrl() : string|null

```php
public getReturnUrl() : string|null
```

**Summary**

Возвращает URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

**Returns:** string|null - URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера


<a name="method_getType" class="anchor"></a>
#### public getType() : ?string

```php
public getType() : ?string
```

**Summary**

Возвращает тип подтверждения платежа.

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)

**Returns:** ?string - 


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


<a name="method_setConfirmationUrl" class="anchor"></a>
#### public setConfirmationUrl() : self

```php
public setConfirmationUrl(string|null $confirmation_url = null) : self
```

**Summary**

Устанавливает URL на который необходимо перенаправить плательщика для подтверждения оплаты

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string OR null</code> | confirmation_url  | URL на который необходимо перенаправить плательщика для подтверждения оплаты |

**Returns:** self - 


<a name="method_setEnforce" class="anchor"></a>
#### public setEnforce() : self

```php
public setEnforce(bool $enforce) : self
```

**Summary**

Устанавливает флаг принудительного подтверждения платежа покупателем

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">bool</code> | enforce  | Требование принудительного подтверждения платежа покупателем, требование 3-D Secure для оплаты банковскими картами. По умолчанию определяется политикой платежной системы. |

**Returns:** self - 


<a name="method_setReturnUrl" class="anchor"></a>
#### public setReturnUrl() : self

```php
public setReturnUrl(string|null $return_url = null) : self
```

**Summary**

Устанавливает URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\ConfirmationRedirect](../classes/YooKassa-Model-Payment-Confirmation-ConfirmationRedirect.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string OR null</code> | return_url  | URL на который вернется плательщик после подтверждения или отмены платежа на странице партнера |

**Returns:** self - 


<a name="method_setType" class="anchor"></a>
#### public setType() : self

```php
public setType(string|null $type = null) : self
```

**Summary**

Устанавливает тип подтверждения платежа

**Details:**
* Inherited From: [\YooKassa\Model\Payment\Confirmation\AbstractConfirmation](../classes/YooKassa-Model-Payment-Confirmation-AbstractConfirmation.md)

##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code lang="php">string OR null</code> | type  | Тип подтверждения платежа |

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