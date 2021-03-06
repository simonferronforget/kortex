# Message Admittance

This page describes the C++ Kinova::Api::Base::Admittance message.

## Overview / Purpose

Defines the admittance mode

## Class members

 **Member variables** 

|Member name|Data type|Description|
|-----------|---------|-----------|
|admittance\_mode| [AdmittanceMode](enm_Base_AdmittanceMode.md#)|mode|

 **Methods** 

The methods listed below are some of the most commonly used. Please refer to Google Protocol Buffer documentation for an exhaustive list.

|Method name|Return type|Input type|Description|
|-----------|-----------|----------|-----------|
|admittance\_mode\(\) const| [AdmittanceMode](enm_Base_AdmittanceMode.md#)|void|Returns the current value of admittance\_mode. If the admittance\_mode is not set, returns 0.|
|set\_admittance\_mode\(\)|void| [AdmittanceMode](enm_Base_AdmittanceMode.md#)|Sets the value of admittance\_mode. After calling this, admittance\_mode\(\) will return value.|
|clear\_admittance\_mode\(\)|void|void|Clears the value of admittance\_mode. After calling this, admittance\_mode\(\) will return the empty string/empty bytes.|

**Parent topic:** [Base](../references/summary_Base.md)

