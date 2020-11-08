# Multi-Factor Authentication Using WhatsApp

## Index 

* [Reactive Architecture](#Reactive-Architecture)
* [Use Case Architecture](#Use-Case-Architecture)
* [Originality and innovation](#Originality-and-innovation)
* [Technical viability](#Technical-viability)
* [Business idea / Project feasibility](#Business-idea-/-Project-feasibility)
* [Impact on the market / Economic feasibility](#Impact-on-the-market-/-Economic-feasibility)

## Reactive Architecture

![](https://github.com/2PWA/docs/blob/main/resources/reactive-architecture.PNG)
    
## Use Case Architecture

![](https://github.com/2PWA/docs/blob/main/resources/use-case-architectures.PNG)

## Originality and innovation

- Decoupled API
- Language independent
- Open to future extensions (Hexagonal Architecture)
- Use of transaction identifiers (UUID)
- OTP submission and verification
- Designed for large flow of requests (Reactive Architecture)

## Technical Viability

Our MVP of the API is going to be developed with the next stack of technologies:

- Java 11 
- Hexagonal Architecure
- Reactive Language(Reactor + WebFlux)
- API WhatsApp Bussiness

In future steps when the application grows we are going to need more technologies with the purpose of giving to the user a better experience:

- Docker
- Kubernetes
- Cloud Provider
- Message Broker
- Load Balancers

So far we know that we need to use some cloud technologies in order to create and scalable, highly available and secure appication ,nevertheless we still dont make the decision about which cloud technologies we are going to use.

## Business idea / Project feasibility

Almost every single company requires a well-developed authentication mechanism, our API was designed with the idea of provide a Multi factor authentication using WhatsApp to medium and large companies.

## Impact on the market / Economic feasibility

