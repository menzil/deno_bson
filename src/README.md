#Usage
`import { Bson } from "https://deno.land/x/bson/mod.ts";`

You can find data from mongodb with document id(ObjectId).

simple:
```typescript
//use with denodb
let objId:any = new Bson.ObjectID(id);
let post  = await PostModel.find(objId);
```
