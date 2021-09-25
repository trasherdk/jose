# Function: exportPKCS8

[key/export](../modules/key_export.md).exportPKCS8

▸ **exportPKCS8**(`key`): `Promise`<`string`\>

Exports a runtime-specific private key representation (KeyObject or CryptoKey) to an PEM-encoded PKCS8 string format.

**`example`** ESM import
```js
import { exportPKCS8 } from 'jose/key/export'
```

**`example`** CJS import
```js
const { exportPKCS8 } = require('jose/key/export')
```

**`example`** Deno import
```js
import { exportPKCS8 } from 'https://deno.land/x/jose@v3.18.0/key/export.ts'
```

**`example`** Usage
```js
const pkcs8Pem = await exportPKCS8(privateKey)

console.log(pkcs8Pem)
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `key` | `Exclude`<[`KeyLike`](../types/types.KeyLike.md), `Uint8Array`\> | Key representation to transform to an PEM-encoded PKCS8 string format. |

#### Returns

`Promise`<`string`\>

#### Defined in

[key/export.ts:65](https://github.com/panva/jose/blob/v3.18.0/src/key/export.ts#L65)