1. yarn 
2. yarn watch 
3. go to dist/restWrapper.js 
4. Replace line 22 with:
   ```import { StandardChunkUploadDocument } from "./classes/StandardChunkUploadDocument.js";```
6. go to dist/index.js
7. replace lines 14, 15, 16, 17 with 
```
import { RestCallWrapper } from "./restWrapper.js";
import { LineEntry } from "./Annotations.js";
import { DialogExpressionCondition, DialogExpression, } from "./DialogExpression.js";
import { StandardChunkUploadDocument } from "./classes/StandardChunkUploadDocument.js";
```

7. in a new terminal run yarn dev 
