# Interface: JWK

## [💗 Help the project](https://github.com/sponsors/panva)

Support from the community to continue maintaining and improving this module is welcome. If you find the module useful, please consider supporting the project by [becoming a sponsor](https://github.com/sponsors/panva).

---

JSON Web Key ([JWK](https://www.rfc-editor.org/rfc/rfc7517)). "RSA", "EC", "OKP", and "oct"
key types are supported.

**`See`**

 - [JWK_OKP_Public](types.JWK_OKP_Public.md)
 - [JWK_OKP_Private](types.JWK_OKP_Private.md)
 - [JWK_EC_Public](types.JWK_EC_Public.md)
 - [JWK_EC_Private](types.JWK_EC_Private.md)
 - [JWK_RSA_Public](types.JWK_RSA_Public.md)
 - [JWK_RSA_Private](types.JWK_RSA_Private.md)
 - [JWK_oct](types.JWK_oct.md)

## Table of contents

### Properties

- [kty](types.JWK.md#kty)
- [alg](types.JWK.md#alg)
- [crv](types.JWK.md#crv)
- [d](types.JWK.md#d)
- [dp](types.JWK.md#dp)
- [dq](types.JWK.md#dq)
- [e](types.JWK.md#e)
- [ext](types.JWK.md#ext)
- [k](types.JWK.md#k)
- [key\_ops](types.JWK.md#key_ops)
- [kid](types.JWK.md#kid)
- [n](types.JWK.md#n)
- [oth](types.JWK.md#oth)
- [p](types.JWK.md#p)
- [q](types.JWK.md#q)
- [qi](types.JWK.md#qi)
- [use](types.JWK.md#use)
- [x](types.JWK.md#x)
- [x5c](types.JWK.md#x5c)
- [x5t](types.JWK.md#x5t)
- [x5t#S256](types.JWK.md#x5t#s256)
- [x5u](types.JWK.md#x5u)
- [y](types.JWK.md#y)

## Properties

### kty

• **kty**: `string`

JWK "kty" (Key Type) Parameter

___

### alg

• `Optional` **alg**: `string`

JWK "alg" (Algorithm) Parameter

**`See`**

[Algorithm Key Requirements](https://github.com/panva/jose/issues/210)

___

### crv

• `Optional` **crv**: `string`

- EC JWK "crv" (Curve) Parameter
- OKP JWK "crv" (The Subtype of Key Pair) Parameter

___

### d

• `Optional` **d**: `string`

- Private RSA JWK "d" (Private Exponent) Parameter
- Private EC JWK "d" (ECC Private Key) Parameter
- Private OKP JWK "d" (The Private Key) Parameter

___

### dp

• `Optional` **dp**: `string`

Private RSA JWK "dp" (First Factor CRT Exponent) Parameter

___

### dq

• `Optional` **dq**: `string`

Private RSA JWK "dq" (Second Factor CRT Exponent) Parameter

___

### e

• `Optional` **e**: `string`

RSA JWK "e" (Exponent) Parameter

___

### ext

• `Optional` **ext**: `boolean`

JWK "ext" (Extractable) Parameter

___

### k

• `Optional` **k**: `string`

Oct JWK "k" (Key Value) Parameter

___

### key\_ops

• `Optional` **key\_ops**: `string`[]

JWK "key_ops" (Key Operations) Parameter

___

### kid

• `Optional` **kid**: `string`

JWK "kid" (Key ID) Parameter

___

### n

• `Optional` **n**: `string`

RSA JWK "n" (Modulus) Parameter

___

### oth

• `Optional` **oth**: \{ `d?`: `string` ; `r?`: `string` ; `t?`: `string`  }[]

Private RSA JWK "oth" (Other Primes Info) Parameter

This parameter is not supported

___

### p

• `Optional` **p**: `string`

Private RSA JWK "p" (First Prime Factor) Parameter

___

### q

• `Optional` **q**: `string`

Private RSA JWK "q" (Second Prime Factor) Parameter

___

### qi

• `Optional` **qi**: `string`

Private RSA JWK "qi" (First CRT Coefficient) Parameter

___

### use

• `Optional` **use**: `string`

JWK "use" (Public Key Use) Parameter

___

### x

• `Optional` **x**: `string`

- EC JWK "x" (X Coordinate) Parameter
- OKP JWK "x" (The public key) Parameter

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

___

### y

• `Optional` **y**: `string`

EC JWK "y" (Y Coordinate) Parameter
