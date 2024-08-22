[![.NET Foundation](https://img.shields.io/badge/.NET%20Foundation-blueviolet.svg?logo=.net&logoColor=white)](https://www.dotnetfoundation.org/) [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![React JS](https://img.shields.io/badge/React%20JS-374151?logo=react&logoColor=61DAFB)](https://react.dev/) ![license](https://img.shields.io/badge/license-MIT-blue.svg)

## SaaS fulfillment APIs in the Microsoft commercial marketplace
The SaaS Fulfillment APIs enable publishers, also known as independent software vendors (ISVs), to publish and sell their SaaS applications in Microsoft AppSource, Azure Marketplace, and Azure portal. These APIs enable ISV applications to participate in all commerce enabled channels: direct, partner-led (reseller), and field-led. Integrating with these APIs is a requirement for creating and publishing a transactable SaaS offer in Partner Center.

## API flows
ISVs must implement the following API flows by adding into their SaaS service code to maintain the same subscription status for both ISVs and Microsoft:

### Landing page flow: 
> Microsoft notifies the publisher that the publisher's SaaS offer was purchased by a customer in the marketplace.

![resolve-subscription](https://github.com/user-attachments/assets/d587ca0c-6f91-40b9-9881-062afe7a29cd)

### Activation flow: 
> Publisher notifies Microsoft that a newly purchased SaaS account was configured on the publisher's side.

![activate-subscription](https://github.com/user-attachments/assets/7f0cdedc-e37d-4ea2-ac83-9692c829475f)

### Webhook flows: 
Microsoft notifies the publisher about SaaS subscription changes and cancellation triggered by the customer from the Microsoft side.

## Powered By Negima-UI Kit
> Negima UI Kit - build using Fluent UI components.

![negima-ui-kit](https://github.com/user-attachments/assets/56c6d698-c69a-4f45-91ee-738bf7352d5c)

## License

Distributed under the MIT License. See [LICENSE](https://github.com/negimatare/saas-fullfilment-isv-management-preview/blob/main/LICENSE) for more information.
