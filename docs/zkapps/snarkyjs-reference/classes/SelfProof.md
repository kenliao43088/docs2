# Class: SelfProof<T\>

## Type parameters

| Name |
| :------ |
| `T` |

## Hierarchy

- [`Proof`](Proof.md)<`T`\>

  ↳ **`SelfProof`**

## Table of contents

### Constructors

- [constructor](SelfProof.md#constructor)

### Properties

- [maxProofsVerified](SelfProof.md#maxproofsverified)
- [proof](SelfProof.md#proof)
- [publicInput](SelfProof.md#publicinput)
- [shouldVerify](SelfProof.md#shouldverify)
- [publicInputType](SelfProof.md#publicinputtype)
- [tag](SelfProof.md#tag)

### Methods

- [toJSON](SelfProof.md#tojson)
- [verify](SelfProof.md#verify)
- [verifyIf](SelfProof.md#verifyif)
- [fromJSON](SelfProof.md#fromjson)

## Constructors

### constructor

• **new SelfProof**<`T`\>(`__namedParameters`)

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `__namedParameters` | `Object` |
| `__namedParameters.maxProofsVerified` | ``0`` \| ``2`` \| ``1`` |
| `__namedParameters.proof` | `unknown` |
| `__namedParameters.publicInput` | `T` |

#### Inherited from

[Proof](Proof.md).[constructor](Proof.md#constructor)

#### Defined in

[lib/proof_system.ts:97](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L97)

## Properties

### maxProofsVerified

• **maxProofsVerified**: ``0`` \| ``2`` \| ``1``

#### Inherited from

[Proof](Proof.md).[maxProofsVerified](Proof.md#maxproofsverified)

#### Defined in

[lib/proof_system.ts:64](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L64)

___

### proof

• **proof**: `unknown`

#### Inherited from

[Proof](Proof.md).[proof](Proof.md#proof)

#### Defined in

[lib/proof_system.ts:63](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L63)

___

### publicInput

• **publicInput**: `T`

#### Inherited from

[Proof](Proof.md).[publicInput](Proof.md#publicinput)

#### Defined in

[lib/proof_system.ts:62](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L62)

___

### shouldVerify

• **shouldVerify**: [`Bool`](Bool.md)

#### Inherited from

[Proof](Proof.md).[shouldVerify](Proof.md#shouldverify)

#### Defined in

[lib/proof_system.ts:65](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L65)

___

### publicInputType

▪ `Static` **publicInputType**: [`ProvablePure`](../interfaces/ProvablePure.md)<`any`\>

#### Inherited from

[Proof](Proof.md).[publicInputType](Proof.md#publicinputtype)

#### Defined in

[lib/proof_system.ts:55](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L55)

___

### tag

▪ `Static` **tag**: () => { `name`: `string`  }

#### Type declaration

▸ (): `Object`

##### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Inherited from

[Proof](Proof.md).[tag](Proof.md#tag)

#### Defined in

[lib/proof_system.ts:56](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L56)

## Methods

### toJSON

▸ **toJSON**(): `JsonProof`

#### Returns

`JsonProof`

#### Inherited from

[Proof](Proof.md).[toJSON](Proof.md#tojson)

#### Defined in

[lib/proof_system.ts:73](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L73)

___

### verify

▸ **verify**(): `void`

#### Returns

`void`

#### Inherited from

[Proof](Proof.md).[verify](Proof.md#verify)

#### Defined in

[lib/proof_system.ts:67](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L67)

___

### verifyIf

▸ **verifyIf**(`condition`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `condition` | [`Bool`](Bool.md) |

#### Returns

`void`

#### Inherited from

[Proof](Proof.md).[verifyIf](Proof.md#verifyif)

#### Defined in

[lib/proof_system.ts:70](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L70)

___

### fromJSON

▸ `Static` **fromJSON**<`S`\>(`this`, `__namedParameters`): [`Proof`](Proof.md)<`InferInstance`<`S`[``"publicInputType"``]\>\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `S` | extends `Subclass`<typeof [`Proof`](Proof.md)\> |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `S` |
| `__namedParameters` | `JsonProof` |

#### Returns

[`Proof`](Proof.md)<`InferInstance`<`S`[``"publicInputType"``]\>\>

#### Inherited from

[Proof](Proof.md).[fromJSON](Proof.md#fromjson)

#### Defined in

[lib/proof_system.ts:82](https://github.com/o1-labs/snarkyjs/blob/4b46575/src/lib/proof_system.ts#L82)