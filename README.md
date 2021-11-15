# Wutsi
<kbd>![](images/architecture.png)</kbd>

| Application | Version | Details |
|-------------|---------|-------------|
| **Client Layer** |
|[wutsi-wallet](https://github.com/wutsi/wutsi_wallet) |  |  |
| **Experience Layer** |
|[Onboard BFF](https://github.com/wutsi/wutsi-onboard-bff)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-onboard-bff) | |
|[Login BFF](https://github.com/wutsi/wutsi-login-bff)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-login-bff) | |
|[Shell BFF](https://github.com/wutsi/wutsi-shell-bff)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-shell-bff) | |
|[Cash BFF](https://github.com/wutsi/wutsi-cash-bff)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-cash-bff) | |
| **Domain Layer** |
|[Account API](https://github.com/wutsi/wutsi-account-server)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-account-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-account-server/api/) |
|[Payment API](https://github.com/wutsi/wutsi-payment-server)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-payment-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-payment-server/api/) |
|[SMS API](https://github.com/wutsi/wutsi-sms-server)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-sms-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-sms-server/api/) |
| **Common Services** |
|[Tenant API](https://github.com/wutsi/wutsi-tenant-server)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-tenant-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-tenant-server/api/)|
|[Security API](https://github.com/wutsi/wutsi-security-server)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-security-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-security-server/api/)|
| **Core Libraries** |
|[sdui](https://github.com/wutsi/sdui)| ![](https://img.shields.io/pub/v/sdui.svg) | Flutter Server Driven UI library |
|[wutsi-platform-payment](https://github.com/wutsi/wutsi-platform-payment)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-platform-payment) | Payment library for mobile payments (MTN, OM etc.) |
|[wutsi-platform-core](https://github.com/wutsi/wutsi-platform-code)| ![](https://img.shields.io/github/v/tag/wutsi/wutsi-platform-core) | |

## Important Architectural Patterns
- Microservices
    - [An Introduction to Micro Services](https://medium.com/microservicegeeks/an-introduction-to-microservices-a3a7e2297ee0)
- Backend for Front End (BFF)
    - [The BFF Pattern (Backend for Frontend): An Introduction](https://blog.bitsrc.io/bff-pattern-backend-for-frontend-an-introduction-e4fa965128bf)
- Server Driven UI (SDUI)
    - [What is Server Driven UI](https://www.judo.app/blog/server-driven-ui/)
