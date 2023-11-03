---
title: Snowflake
sidebar:
  order: 16
---



## Snowflake
Represents a Snowflake, a unique identifier used in distributed systems.

**Kind**: global class  

* [Snowflake](#Snowflake)
    * [.deconstruct(snowflake)](#Snowflake.deconstruct) ⇒ <code>Object</code>
    * [.generate([timestamp])](#Snowflake.generate) ⇒ <code>string</code>

<a name="Snowflake.deconstruct"></a>

### Snowflake.deconstruct(snowflake) ⇒ <code>Object</code>
Deconstructs a Discord snowflake into its individual components.

**Kind**: static method of [<code>Snowflake</code>](#Snowflake)  
**Returns**: <code>Object</code> - An object containing the deconstructed components of the snowflake:

| Param | Type | Description |
| --- | --- | --- |
| snowflake | <code>string</code> | The snowflake to deconstruct. |

<a name="Snowflake.generate"></a>

### Snowflake.generate([timestamp]) ⇒ <code>string</code>
Generates a unique ID based on the given timestamp.

**Kind**: static method of [<code>Snowflake</code>](#Snowflake)  
**Returns**: <code>string</code> - - The generated unique ID.  
**Throws**:

- <code>TypeError</code> - If the timestamp is not a number or a valid Date object.


| Param | Type | Default | Description |
| --- | --- | --- | --- |
| [timestamp] | <code>number</code> \| <code>Date</code> | <code>Date.now()</code> | The timestamp to generate the ID from. |
