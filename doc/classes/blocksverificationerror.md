[etcher-sdk](../README.md) › [BlocksVerificationError](blocksverificationerror.md)

# Class: BlocksVerificationError

## Hierarchy

  ↳ [VerificationError](verificationerror.md)

  ↳ **BlocksVerificationError**

## Index

### Constructors

* [constructor](blocksverificationerror.md#constructor)

### Properties

* [blocks](blocksverificationerror.md#blocks)
* [checksum](blocksverificationerror.md#checksum)
* [code](blocksverificationerror.md#code)
* [message](blocksverificationerror.md#message)
* [name](blocksverificationerror.md#name)
* [stack](blocksverificationerror.md#optional-stack)

## Constructors

###  constructor

\+ **new BlocksVerificationError**(`blocks`: [BlocksWithChecksum](../interfaces/blockswithchecksum.md), `checksum`: string): *[BlocksVerificationError](blocksverificationerror.md)*

*Defined in [lib/errors.ts:48](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/errors.ts#L48)*

**Parameters:**

Name | Type |
------ | ------ |
`blocks` | [BlocksWithChecksum](../interfaces/blockswithchecksum.md) |
`checksum` | string |

**Returns:** *[BlocksVerificationError](blocksverificationerror.md)*

## Properties

###  blocks

• **blocks**: *[BlocksWithChecksum](../interfaces/blockswithchecksum.md)*

*Defined in [lib/errors.ts:50](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/errors.ts#L50)*

___

###  checksum

• **checksum**: *string*

*Defined in [lib/errors.ts:51](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/errors.ts#L51)*

___

###  code

• **code**: *string* = "EVALIDATION"

*Inherited from [VerificationError](verificationerror.md).[code](verificationerror.md#code)*

*Defined in [lib/errors.ts:24](https://github.com/balena-io-modules/etcher-sdk/blob/e5355bd/lib/errors.ts#L24)*

___

###  message

• **message**: *string*

*Inherited from [NotCapable](notcapable.md).[message](notcapable.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:974

___

###  name

• **name**: *string*

*Inherited from [NotCapable](notcapable.md).[name](notcapable.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:973

___

### `Optional` stack

• **stack**? : *undefined | string*

*Inherited from [NotCapable](notcapable.md).[stack](notcapable.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:975
