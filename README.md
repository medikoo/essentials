# essentials

## Essential initialization for every JavaScript process

Ensures that:

-   Error stack traces list all stack frames
-   Unhandled promise rejections are exposed as uncaught exceptions

### Installation

```bash
npm install essentials
```

### Usage

At top of main (entry) module simply require

```javascript
require("essentials");
```
