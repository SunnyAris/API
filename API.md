### An Application Programming Interface (API) is a contract that allows a computer program to talk to other computer programs. APIs are the building blocks of modern software because they allow for the sharing of resources and services across applications, organizations, and devices.

- Customer = Client (typically a browser, web app or mobile app)

- Waiter = API (interface for interacting with the backend)

- Kitchen = Server (backend where the processing happens)


## API types

The term API is often used to refer to web APIs, which allow communication between computers that are joined by the internet. While this course will focus on Web APIs, it is important to keep in mind that the term "API" can apply to a broad range of interfaces:

- A hardware API is an interface for software to talk to hardware.

Ex: How your phone's camera talks to the operating system.


- A software library API is an interface for directly consuming code from another code base.

Ex: Using methods from a library you import into your application.


- A web API is an interface for communicating across code bases over a network.

Ex: Fetching current stock prices from a finance API over the internet.


Multiple API types may be used to achieve a simple task. For example, uploading a photo to Instagram makes use of various APIs:

- Hardware API for the app to talk to your camera

- Software library API for the image to be processed with filters

- Web API for sending your image to Instagram's servers so your friends can like it



### API architectures

*There is more than one way to build and consume APIs. These are some of the most common architecture types you may come across:

- REST (Representational State Transfer)

- GraphQL

- WebSockets

- webhooks

- SOAP (Simple Object Access Protocol)

- gRPC (Google Remote Procedure Call)

- MQTT (MQ Telemetry Transport)


### API accessibility

APIs also vary in the scope of who can access them:

- Public APIs are consumed by anyone who discovers the API

- Private APIs are consumed only within an organization and are not made public

- Partner APIs are consumed between one or more organizations that have an established relationship
