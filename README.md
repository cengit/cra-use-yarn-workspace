# cra-use-yarn-workspace
create react app to use yarn workspace as a dependency

## problems

```js
// error when I use this code
import { fn } from 'yarn-work-space-demo'; 
 
/* ========= error detail =========
Compiled with problems:X

ERROR in ./node_modules/yarn-work-space-demo/index.js 1:0-22

Module not found: Error: Can't resolve 'pkg-a' in '/Users/cen/code/github/cra/cra-use-yarn-workspace/node_modules/yarn-work-space-demo'

ERROR in ./node_modules/yarn-work-space-demo/index.js 2:0-28
*/
```


