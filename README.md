# deno_bson
You can find data from mongodb with ObjectId

// find by ObjectId
const user1_id = await users.findOne({ _id: new Bson.ObjectId("SOME OBJECTID STRING") });

froked from [deno_mongo](https://github.com/manyuanrong/deno_mongo/)