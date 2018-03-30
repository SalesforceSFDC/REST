# REST

* [Apex REST Annotations](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_classes_annotations_rest.htm)
* [RestContext Class](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_methods_system_restcontext.htm#apex_methods_system_restcontext)
* [JSON Support](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_methods_system_json_overview.htm)
* [Apex Web Services and Callouts](https://developer.salesforce.com/page/Apex_Web_Services_and_Callouts)
* [Invoking HTTP Callouts](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_callouts_http.htm)
* [Asynchronous Callout Limits](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_continuation_limits.htm)
* [Testing HTTP Callouts](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apexcode/apex_classes_restful_http_testing.htm)
* [Apex REST Callouts](https://trailhead.salesforce.com/en/modules/apex_integration_services/units/apex_integration_rest_callouts)
## Apex REST Methods
You can retrieve the body as a Blob from the HttpRequest object if there are no parameters to the Apex method. If parameters are defined in the Apex method, an attempt is made to deserialize the request body into those parameters. If the Apex method has a non-void return type, the resource representation is serialized into the response body.
* Apex primitives (excluding sObject and Blob).
* sObjects
* Lists or maps of Apex primitives or sObjects (only maps with String keys are supported).
* User-defined types that contain member variables of the types listed above.
