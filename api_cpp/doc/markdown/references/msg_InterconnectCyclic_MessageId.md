# Message MessageId

This page describes the C++ Kinova::Api::InterconnectCyclic::MessageId message.

## Overview / Purpose

Identifies a message

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|identifier|uint32|Message ID \(first 2 bytes : device ID, last 2 bytes : sequence number\)|

 **Methods** 

The methods listed below are some of the most commonly used. Please refer to Google Protocol Buffer documentation for an exhaustive list.

|Method name|Return type|Input type|Description|
|-----------|-----------|----------|-----------|
|identifier\(\)|uint32|void|Returns the current value of identifier. If the identifier is not set, returns 0.|
|set\_identifier\(\)|void|uint32|Sets the value of identifier. After calling this, identifier\(\) will return value.|
|clear\_identifier\(\)|void|void|Clears the value of identifier. After calling this, identifier\(\) will return 0.|

**Parent topic:** [InterconnectCyclic](../references/summary_InterconnectCyclic.md)

