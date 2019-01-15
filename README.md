# essentials

## Essential initialization for every JavaScript process

Ensures that:

#### Error stack traces list all stack frames

Affects all major engines aside Firefox, which has this setting not adjustable and hardcoded to 128.

#### Unhandled promise rejections are exposed as uncaught exceptions

Affects all V8 based engines (so Chrome and Node.js) and Microsoft Edge

In other engines it is recommended to rely on some `Promise` polyfill, which ensures unhandled rejections being communicated in programmatically consumable way.

### Installation

```bash
npm install essentials
```

### Usage

At top of main (entry) module simply require

```javascript
require("essentials");
```
