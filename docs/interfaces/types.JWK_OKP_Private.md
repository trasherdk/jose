# Interface: JWK\_OKP\_Private

## [💗 Help the project](https://github.com/sponsors/panva)

Support from the community to continue maintaining and improving this module is welcome. If you find the module useful, please consider supporting the project by [becoming a sponsor](https://github.com/sponsors/panva).

---

Convenience interface for Private OKP JSON Web Keys

## Table of contents

### Properties

- [crv](types.JWK_OKP_Private.md#crv)
- [d](types.JWK_OKP_Private.md#d)
- [kty](types.JWK_OKP_Private.md#kty)
- [x](types.JWK_OKP_Private.md#x)
- [alg](types.JWK_OKP_Private.md#alg)
- [ext](types.JWK_OKP_Private.md#ext)
- [key\_ops](types.JWK_OKP_Private.md#key_ops)
- [kid](types.JWK_OKP_Private.md#kid)
- [use](types.JWK_OKP_Private.md#use)
- [x5c](types.JWK_OKP_Private.md#x5c)
- [x5t](types.JWK_OKP_Private.md#x5t)
- [x5t#S256](types.JWK_OKP_Private.md#x5t#s256)
- [x5u](types.JWK_OKP_Private.md#x5u)

## Properties

### crv

• **crv**: `string`

OKP JWK "crv" (The Subtype of Key Pair) Parameter

___

### d

• **d**: `string`

OKP JWK "d" (The Private Key) Parameter

___

### kty

• **kty**: `string`

JWK "kty" (Key Type) Parameter

___

### x

• **x**: `string`

OKP JWK "x" (The public key) Parameter

___

### alg

• `Optional` **alg**: `string`

JWK "alg" (Algorithm) Parameter

**`See`**

[Algorithm Key Requirements](https://github.com/panva/jose/issues/210)

___

### ext

• `Optional` **ext**: `boolean`

JWK "ext" (Extractable) Parameter

___

### key\_ops

• `Optional` **key\_ops**: `string`[]

JWK "key_ops" (Key Operations) Parameter

___

### kid

• `Optional` **kid**: `string`

JWK "kid" (Key ID) Parameter

___

### use

• `Optional` **use**: `string`

JWK "use" (Public Key Use) Parameter

___

### x5c

• `Optional` **x5c**: `string`[]

JWK "x5c" (X.509 Certificate Chain) Parameter

___

### x5t

• `Optional` **x5t**: `string`

JWK "x5t" (X.509 Certificate SHA-1 Thumbprint) Parameter

___

### x5t#S256

• `Optional` **x5t#S256**: `string`

JWK "x5t#S256" (X.509 Certificate SHA-256 Thumbprint) Parameter

___

### x5u

• `Optional` **x5u**: `string`

JWK "x5u" (X.509 URL) Parameter
