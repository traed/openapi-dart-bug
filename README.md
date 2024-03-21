# Test API
Minimal repo to demonstrate a bug

## Usage
`./generate.sh /local/openapi.json`

Change the OpenAPI version from 3.0.0 to 3.1.0 and then inspect the file `sdk/lib/model/list_things200_response.dart` on line 19. For v3.0.0 this type is a `List<Thing>` but for v3.1.0 it's `Object?`.