## JSON Service defines a standard for describing any JSON HTTP/REST API using JSON meta data. ##

**JSON+HTTP**, including **REST-JSON** is clearly the most popular method of making services available on the web because it is **lightweight**, has a **low barrier to entry for integration**, and allows the easy creation of **AJAX style applications**, as well as server side integration.

However, the service meta-data of SOAP (WSDL), available due to its contractual nature, gives clear benefits around code generation, message validation and documentation.

By **augmenting JSON+HTTP services with meta-data** based around the great work being done on **[JSON Schema](http://json-schema.org)**, many benefits could be realised, **beyond those of WSDL**.

The meta-data will be in the form of a JSON Service Descriptor, or **JDS**, file, analogous to a WSDL file.

Benefits that could be realized include:

  * A **standard way of describing a service**, and the operations that can be carried out on its resources, through meta-data.
  * A standard way to lookup different service **versions** and their URLs;
  * **No need for separate documentation** - documentation can be auto-generated; a javascript utility is planned.
  * Allows for sync and async auto-generated client APIs and client validation (Java/.NET/etc.)
  * **Programmatic integration.**
  * Allows for **programmatically generated UI**.
  * Allows the creation service **"interfaces"**, such that **different implementations can be chosen and configured at run-time**;
  * Allows **existing APIs** to be **easily augmented, not changed**, to adhere to the standard.
  * Increased **code reuse**.
  * Automatic JDS generation from source code.
  * On the fly JDS <=> SMD conversion/interoperation.

The [Specification](Specification.md) is currently under development - come and join our [Google Group](http://groups.google.com/group/json-service) to get involved!

The "JSON Service" [Specification](Specification.md) was proprietary work by [Matthew Painter](mailto:matthew.painter@kusiri.com) of [Kusiri](http://www.kusiri.com), a London based software company, before being Open Sourced in January 2010.