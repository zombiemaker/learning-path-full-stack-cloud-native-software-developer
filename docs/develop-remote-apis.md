# Develop Remote Application Programming Interfaces (APIs)

## Categories / Types Of APIs

* REST / JSON = HTTP + JSON
* REST / JSON:API = HTTP + JSON:API
* REST / JSON Schema = HTTP + JSON Schema
* REST / OpenAPI
* REST / JSON
* REST / XML = HTTP + XML
* GraphQL = HTTP + JSON
* gRPC = gRPC + Protobufs
* Hypermedia = HTTP + content negotiation
* HTTP / JSON-LD



## Basics


* General REST APIs
  * [REST APIs Must Be Hypertext-Driven (Roy Fielding)](https://roy.gbiv.com/untangled/2008/rest-apis-must-be-hypertext-driven)
* Develop Hypermedia HTTP APIs
  * [REST, Hypermedia, And The Semantic Gap (Mike Amundsen) (2015)](https://learning.oreilly.com/videos/rest-hypermedia-and/9781491936511/)
  * [Design APIs For The Web (Mike Amundsen) (2014)](https://learning.oreilly.com/videos/designing-apis-for/9781491900147/)
  * [RESTful Web Microservices From The Ground Up (Mike Amundsen) (2019)](https://learning.oreilly.com/videos/restful-web-microservices/0636920362746/)
  * [Resource-Oriented Architectures: Hypermedia (Brian Sletten) (2015)](https://learning.oreilly.com/videos/resource-oriented-architectures-hypermedia/9781491924877)
  * [Building Hypermedia APIs With HTML5 And Node (Mike Amundsen) (2011)](https://learning.oreilly.com/library/view/building-hypermedia-apis/9781449309497/)
  * [RESTful Web APIs (Amundsen, Ruby, Richardson)](https://learning.oreilly.com/library/view/restful-web-apis/9781449359713/)
  * [REST API Development With Node.js: Manage And Understand The Full Capabilities Of Successful REST Development (Fernando Doglio) (2018)](https://learning.oreilly.com/library/view/rest-api-development/9781484237151/)
  * [RESTful Web API Design With Node.js 12 (Florian Goto) (2020)](https://learning.oreilly.com/videos/restful-web-api/9781838648770)
  * [Building A Scalable Serverless Microservice REST Data API (Richard T. Freeman) (2018)](https://learning.oreilly.com/videos/building-a-scalable/9781788622318)
* General HTTP/HTTPS (i.e. Web) APIs
  * [Understanding APIs And RESTful APIs Crash Course (Kalob Taulien) (2020)](https://learning.oreilly.com/videos/understanding-apis-and/9781800564121/)
  * [The Design Of Web APIs (Arnaud Lauret) (2019)](https://learning.oreilly.com/library/view/the-design-of/9781617295102/)  
  * [Designing Web APIs (Jin, Sahni, Shevat) (2018)](https://learning.oreilly.com/library/view/designing-web-apis/9781492026914/)
  * [Irresistible APIs (Kirsten Hunter) (2016)](https://learning.oreilly.com/library/view/irresistible-apis/9781617292552/)
  * [APIs For Modern Commerce (Kelly Goetsch) (2017)](https://learning.oreilly.com/library/view/apis-for-modern/9781491995266/)
  * [CORS In Action: Creating And Consuming Cross-Origin APIs (2014)](https://learning.oreilly.com/library/view/cors-in-action/9781617291821/)
* Develop RPC HTTP APIs
  * [Mastering REST APIs In Node.js: Zero To Hero (2019)](https://learning.oreilly.com/videos/mastering-rest-apis/9781838825232)
  * [Hands-On RESTful Web Services With TypeScript 3 (Biharck Muniz Araujo) (2019)](https://learning.oreilly.com/library/view/hands-on-restful-web/9781789956276/)
* Develop GraphQL HTTP APIs
* Develop Linked Data Information Resource HTTP APIs
* Develop Websocket APIs
* Develop Messaging / AMQP APIs
* Develop Messaging / MQTT APIs
* Develop Messaging / NATS APIs
* Develop Messaging / NSQ APIs
* Develop WebRTC APIs

## Advanced

* [API Testing With Postman (Dave Westerveld) (2019)](https://learning.oreilly.com/videos/api-testing-with/9781789616569/)
* [Enterprise API Management (Weir, Nemec) (2019)](https://learning.oreilly.com/library/view/enterprise-api-management/9781787284432/)

## Resources

* [JSON Schema](https://json-schema.org/)
* [JSON:API](https://jsonapi.org/)
* [OpenAPI](https://www.openapis.org/)
* [JSON-LD](https://json-ld.org/)
* [gRPC](https://grpc.io/)
* [JSON RPC](https://jsonrpc.org/)
* [Apache Avro](https://avro.apache.org/)
* [Apache Thrift](https://thrift.apache.org/)
* [NSQ](https://nsq.io/)

## Concepts

* Remote API Types
  * RPC APIs
  * REST APIs
* HTTP Remote API Programming Models
  * Type Marshaling / Serialization Remote API Programming Model
    * Shared Schema (e.g., SOAP)
    * URI Construction API (e.g., /salesorders, /salesorders/123)
    * Payload Decoration API (e.g. { "_type": "SalesOrder" } JSON message)
    * Narrow Media Type API (e.g. application/salesorder+json MIME type / HTTP content type)
  * Hypermedia Remote API Programming Model
* Inter-Application Message Data Structuring Formats
  * XML
  * JSON
  * HTML
  * Apache Avro
  * Google Protocol Buffers