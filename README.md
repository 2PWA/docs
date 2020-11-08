# Multi-Factor Authentication Using WhatsApp

## Index 

* [Reactive Architecture](#Reactive-Architecture)
* [Use Case Architecture](#Use-Case-Architecture)
* [Originality and innovation](#Originality-and-innovation)
* [Technical viability](#Technical-viability)
* [Business idea and Project feasibility](#Business-idea-and-Project-feasibility)
* [Impact on the market and Economic feasibility](#Impact-on-the-market-and-Economic-feasibility)

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

## Business idea and Project feasibility

Almost every single company requires a well-developed authentication mechanism, our API was designed with the idea of provide a Multi factor authentication using WhatsApp to medium and large companies.

- Fristly the users that want to use the API are going to need a monthly suscription with a fixed price.

- Secondly users registered to the API are going to pay for every message sent.

## Impact on the market and Economic feasibility

As we know in current days there are thousand of new application in the market, all of those application are our target market.

### Cost per Moth

Be aware that cost are going to chaneg with time, when the application get bigger the cost are going to grow too.

- Servers: 25USD
- Domain: 1USD
- DB: 15USD
- Proxy: 25USD
- Implementation: 4500 (15 USD per hour/300 hour per month)

Total amount per month : 4566 USD

### Reveneu per Moth

#### Fixed Price

One of the ways to get a reveneu for this project is with a monthly subscription of 10 USD.

#### Messages Sent

In order to understand how to achieve a reveneu with the messages sent, we need to check the next table.

![](https://github.com/2PWA/docs/blob/main/resources/cost-per-messages.PNG)

As you can see in the above table, the messages sent get cheaper when the application grows in the amount of the messages sent, so our idea is to charge every user with the most expensive price and when the application grows our reveneu are going to be the difference between the most expensive price and the custom price.

`reveneu = (amountTransactions * basePrice) -  (amountTransactions * customPrice) `

<table style="width:100%">
  <tr>
    <th>Days Month</th>
    <th># Workers</th>
    <th># Message Sent</th>
    <th># Companies</th>
    <th># Messages per Motht</th>
    <th>Cost per Company</th>
    <th>Base Price</th>
    <th>Custom Price</th>
    <th>Reveneu</th>
  </tr>
  <tr>
    <td>20</td>
    <td>10</td>
    <td>5</td>
    <td>20</td>
    <td>20000</td>
    <td>10</td>
    <td>200</td>
    <td>200</td>
    <td>0</td>
  </tr>
  <tr>
    <td>20</td>
    <td>20</td>
    <td>10</td>
    <td>40</td>
    <td>160000</td>
    <td>40</td>
    <td>1600</td>
    <td>1600</td>
    <td>0</td>
  </tr>
  <tr>
    <td>20</td>
    <td>25</td>
    <td>20</td>
    <td>50</td>
    <td>500000</td>
    <td>100</td>
    <td>5000</td>
    <td>4875</td>
    <td>125</td>
  </tr>
    <tr>
    <td>20</td>
    <td>50</td>
    <td>40</td>
    <td>100</td>
    <td>4000000</td>
    <td>400</td>
    <td>40000</td>
    <td>36025</td>
    <td>3975</td>
  </tr>
</table>
