[slopes - v1.4.3](../README.md) › [Globals](../globals.md) › ["apis/avm/types"](../modules/_apis_avm_types_.md) › [SigIdx](_apis_avm_types_.sigidx.md)

# Class: SigIdx

Type representing a [Signature](_apis_avm_types_.signature.md) index used in [Input](_apis_avm_inputs_.input.md)

## Hierarchy

* [NBytes](_utils_types_.nbytes.md)

  ↳ **SigIdx**

## Index

### Constructors

* [constructor](_apis_avm_types_.sigidx.md#constructor)

### Properties

* [bsize](_apis_avm_types_.sigidx.md#protected-bsize)
* [bytes](_apis_avm_types_.sigidx.md#protected-bytes)
* [source](_apis_avm_types_.sigidx.md#source)

### Methods

* [fromBuffer](_apis_avm_types_.sigidx.md#frombuffer)
* [fromString](_apis_avm_types_.sigidx.md#fromstring)
* [getSize](_apis_avm_types_.sigidx.md#getsize)
* [getSource](_apis_avm_types_.sigidx.md#getsource)
* [setSource](_apis_avm_types_.sigidx.md#setsource)
* [toBuffer](_apis_avm_types_.sigidx.md#tobuffer)
* [toString](_apis_avm_types_.sigidx.md#tostring)

## Constructors

###  constructor

\+ **new SigIdx**(): *[SigIdx](_apis_avm_types_.sigidx.md)*

*Overrides [NBytes](_utils_types_.nbytes.md).[constructor](_utils_types_.nbytes.md#constructor)*

*Defined in [apis/avm/types.ts:33](https://github.com/ava-labs/slopes/blob/709e172/src/apis/avm/types.ts#L33)*

Type representing a [Signature](_apis_avm_types_.signature.md) index used in [Input](_apis_avm_inputs_.input.md)

**Returns:** *[SigIdx](_apis_avm_types_.sigidx.md)*

## Properties

### `Protected` bsize

• **bsize**: *number*

*Inherited from [NBytes](_utils_types_.nbytes.md).[bsize](_utils_types_.nbytes.md#protected-bsize)*

*Defined in [utils/types.ts:400](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L400)*

___

### `Protected` bytes

• **bytes**: *Buffer*

*Inherited from [NBytes](_utils_types_.nbytes.md).[bytes](_utils_types_.nbytes.md#protected-bytes)*

*Defined in [utils/types.ts:399](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L399)*

___

###  source

• **source**: *Buffer*

*Defined in [apis/avm/types.ts:19](https://github.com/ava-labs/slopes/blob/709e172/src/apis/avm/types.ts#L19)*

## Methods

###  fromBuffer

▸ **fromBuffer**(`buff`: Buffer): *number*

*Inherited from [NBytes](_utils_types_.nbytes.md).[fromBuffer](_utils_types_.nbytes.md#frombuffer)*

*Defined in [utils/types.ts:433](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L433)*

Takes a [[Buffer]], verifies its length, and stores it.

**Parameters:**

Name | Type |
------ | ------ |
`buff` | Buffer |

**Returns:** *number*

The size of the [Buffer](https://github.com/feross/buffer)

___

###  fromString

▸ **fromString**(`b58str`: string): *number*

*Inherited from [NBytes](_utils_types_.nbytes.md).[fromString](_utils_types_.nbytes.md#fromstring)*

*Defined in [utils/types.ts:416](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L416)*

Takes a base-58 encoded string, verifies its length, and stores it.

**Parameters:**

Name | Type |
------ | ------ |
`b58str` | string |

**Returns:** *number*

The size of the [Buffer](https://github.com/feross/buffer)

___

###  getSize

▸ **getSize**(): *number*

*Inherited from [NBytes](_utils_types_.nbytes.md)*

*Defined in [utils/types.ts:407](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L407)*

Returns the length of the [Buffer](https://github.com/feross/buffer).

**Returns:** *number*

The exact length requirement of this class

___

###  getSource

▸ **getSource**(): *Buffer*

*Defined in [apis/avm/types.ts:31](https://github.com/ava-labs/slopes/blob/709e172/src/apis/avm/types.ts#L31)*

Retrieves the source address for the signature

**Returns:** *Buffer*

___

###  setSource

▸ **setSource**(`address`: Buffer): *void*

*Defined in [apis/avm/types.ts:24](https://github.com/ava-labs/slopes/blob/709e172/src/apis/avm/types.ts#L24)*

Sets the source address for the signature

**Parameters:**

Name | Type |
------ | ------ |
`address` | Buffer |

**Returns:** *void*

___

###  toBuffer

▸ **toBuffer**(): *Buffer*

*Inherited from [NBytes](_utils_types_.nbytes.md).[toBuffer](_utils_types_.nbytes.md#tobuffer)*

*Defined in [utils/types.ts:454](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L454)*

Returns the stored [Buffer](https://github.com/feross/buffer).

**Returns:** *Buffer*

A reference to the stored [Buffer](https://github.com/feross/buffer)

___

###  toString

▸ **toString**(): *string*

*Inherited from [NBytes](_utils_types_.nbytes.md).[toString](_utils_types_.nbytes.md#tostring)*

*Defined in [utils/types.ts:463](https://github.com/ava-labs/slopes/blob/709e172/src/utils/types.ts#L463)*

Returns a base-58 string of the stored [Buffer](https://github.com/feross/buffer).

**Returns:** *string*

A base-58 string of the stored [Buffer](https://github.com/feross/buffer)
