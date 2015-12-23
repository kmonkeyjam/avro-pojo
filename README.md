# avro-pojo
This is a set of templates that takes an avro record and builds a plain java object with getters and setters along with a builder.  Enums are supported but union and exceptions are not.

These modifications limit the default avro record functionality:
- Default values do not work
- No field validation 
- No hasField methods
