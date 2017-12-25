# JSON Store

JSON Store is a library which maintains a JSON file with order-preserving
mappings from arbitrary strings to any kind of JSON values (a string, an
object, etc). IDs can be either randomly generated or custom.

The order in which items are stored in the file and iterated (with
[`mgos_jstore_iterate()`](https://mongoose-os.com/docs/api/mgos_jstore.h.html#mgos_jstore_iterate))
is the order of insertion of items to the store.

Refer to the [API documentation](https://mongoose-os.com/docs/api/mgos_jstore.h.html)
for details.
