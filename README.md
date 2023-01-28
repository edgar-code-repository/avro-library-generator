AVRO LIBRARY GENERATOR
-----------------------------------------------------------------

An Avro schema is created in the directory "src/main/avro":

```

{
  "type" : "record",
  "name" : "AvroMessageDTO",
  "namespace" : "com.domain.example.dto",
  "fields" : [
    { "name" : "code", "type" : "int" },
    { "name" : "message",  "type" : "string" },
    { "name" : "description",  "type" : "string" }
  ]
}

```

-----------------------------------------------------------------
