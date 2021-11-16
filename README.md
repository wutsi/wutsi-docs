# Wutsi
<kbd>![](images/architecture.png)</kbd>

| Application | Status | Version | Details |
|-------------|--------|----------|-------------|
| **Client Layer** |
|[wutsi-wallet](https://github.com/wutsi/wutsi_wallet) | ![](https://github.com/wutsi/wutsi_wallet/actions/workflows/master.yml/badge.svg) |  | |
| **Experience Layer** |
|[Onboard BFF](https://github.com/wutsi/wutsi-onboard-bff)| ![](https://github.com/wutsi/wutsi-onboard-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-onboard-bff) | |
|[Login BFF](https://github.com/wutsi/wutsi-login-bff)| ![](https://github.com/wutsi/wutsi-login-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-login-bff) | |
|[Shell BFF](https://github.com/wutsi/wutsi-shell-bff)| ![](https://github.com/wutsi/wutsi-shell-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-shell-bff) | |
|[Cash BFF](https://github.com/wutsi/wutsi-cash-bff)| ![](https://github.com/wutsi/wutsi-cash-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-cash-bff) | |
| **Domain Layer** |
|[Account API](https://github.com/wutsi/wutsi-account-server)| ![](https://github.com/wutsi/wutsi-account-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-account-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-account-server/api/) |
|[Payment API](https://github.com/wutsi/wutsi-payment-server)| ![](https://github.com/wutsi/wutsi-payment-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-payment-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-payment-server/api/) |
|[SMS API](https://github.com/wutsi/wutsi-sms-server)| ![](https://github.com/wutsi/wutsi-sms-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-sms-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-sms-server/api/) |
| **Common Services** |
|[Tenant](https://github.com/wutsi/wutsi-tenant-server)| ![](https://github.com/wutsi/wutsi-tenant-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-tenant-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-tenant-server/api/) - Supports for multi-tenancy |
|[Security](https://github.com/wutsi/wutsi-security-server)| ![](https://github.com/wutsi/wutsi-security-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-security-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-security-server/api/) - Manages authentication, authorization |
| Analytics |  | Collects all the platform signals |
| Monitoring |  | Monitors the platform |
| **Core Libraries** |
|[sdui](https://github.com/wutsi/sdui)| ![](https://github.com/wutsi/sdui/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/pub/v/sdui.svg) | Flutter Server Driven UI library |
|[wutsi-platform-payment](https://github.com/wutsi/wutsi-platform-payment)| ![](https://github.com/wutsi/wutsi-platform-payment/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-platform-payment) | Payment library for mobile payments (MTN, OM etc.) |
|[wutsi-platform-core](https://github.com/wutsi/wutsi-platform-core)| ![](https://github.com/wutsi/wutsi-platform-core/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-platform-core) | |
|[wutsi-openapi](https://github.com/wutsi/wutsi-openapi)| | API in OpenAPI schemas |
|[wutsi-codegen](https://github.com/wutsi/wutsi-codegen)| ![](https://github.com/wutsi/wutsi-codegen/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-codegen) | OpenAPI to Kotlin code generateor |

## Important Architectural Patterns
- [An Introduction to Micro Services](https://medium.com/microservicegeeks/an-introduction-to-microservices-a3a7e2297ee0)
- [The BFF Pattern (Backend for Frontend): An Introduction](https://blog.bitsrc.io/bff-pattern-backend-for-frontend-an-introduction-e4fa965128bf)
- [What is Server Driven UI](https://www.judo.app/blog/server-driven-ui/)
