# Interface: JWKParameters

## [💗 Help the project](https://github.com/sponsors/panva)

Support from the community to continue maintaining and improving this module is welcome. If you find the module useful, please consider supporting the project by [becoming a sponsor](https://github.com/sponsors/panva).

Generic JSON Web Key Parameters.

## Properties

### kty

• **kty**: `string`

JWK "kty" (Key Type) Parameter

***

### alg?

• `optional` **alg**: `string`

JWK "alg" (Algorithm) Parameter

#### See

[Algorithm Key Requirements](https://github.com/panva/jose/issues/210)

***

### ext?

• `optional` **ext**: `boolean`

JWK "ext" (Extractable) Parameter

***

### key\_ops?

• `optional` **key\_ops**: `string`[]

JWK "key_ops" (Key Operations) Parameter

***

### kid?

• `optional` **kid**: `string`

JWK "kid" (Key ID) Parameter

***

### use?

• `optional` **use**: `string`

JWK "use" (Public Key Use) Parameter

***

### x5c?

• `optional` **x5c**: `string`[]

JWK "x5c" (X.509 Certificate Chain) Parameter

***

### x5t?

• `optional` **x5t**: `string`

JWK "x5t" (X.509 Certificate SHA-1 Thumbprint) Parameter

***

### x5t#S256?

• `optional` **x5t#S256**: `string`

JWK "x5t#S256" (X.509 Certificate SHA-256 Thumbprint) Parameter

***

### x5u?

• `optional` **x5u**: `string`

JWK "x5u" (X.509 URL) Parameter