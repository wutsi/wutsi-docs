# Wutsi
<kbd>![](images/architecture.png)</kbd>

| Application | Status | Version | Details |
|-------------|--------|----------|-------------|
| **Client Layer** |
|[wutsi_wallet](https://github.com/wutsi/wutsi_wallet) | ![](https://github.com/wutsi/wutsi_wallet/actions/workflows/master.yml/badge.svg) |  | |
| **Experience Layer** |
|[Onboard BFF](https://github.com/wutsi/wutsi-onboard-bff)| ![](https://github.com/wutsi/wutsi-onboard-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-onboard-bff) | |
|[Login BFF](https://github.com/wutsi/wutsi-login-bff)| ![](https://github.com/wutsi/wutsi-login-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-login-bff) | |
|[Shell BFF](https://github.com/wutsi/wutsi-shell-bff)| ![](https://github.com/wutsi/wutsi-shell-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-shell-bff) | |
|[Cash BFF](https://github.com/wutsi/wutsi-cash-bff)| ![](https://github.com/wutsi/wutsi-cash-bff/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-cash-bff) | |
| **Domain Layer** |
|[Account API](https://github.com/wutsi/wutsi-account-server)| ![](https://github.com/wutsi/wutsi-account-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-account-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-account-server/api/) |
|[Payment API](https://github.com/wutsi/wutsi-payment-server)| ![](https://github.com/wutsi/wutsi-payment-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-payment-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-payment-server/api/) |
|[Contact API](https://github.com/wutsi/wutsi-contact-server)| ![](https://github.com/wutsi/wutsi-contact-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-contact-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-contact-server/api/) |
|[Notification API](https://github.com/wutsi/wutsi-notification-server)| ![](https://github.com/wutsi/wutsi-notification-server/actions/workflows/master.yml/badge.svg) |  | Send notifications to users via SMS/Email or PushNotification |
|[Heroku Launcher](https://github.com/wutsi/wutsi-heroku-launcher)| ![](https://github.com/wutsi/wutsi-heroku-launcher/actions/workflows/master.yml/badge.svg) |  | Relaunch server shutdown because of their inactivity |
| **Common Services** |
|[Tenant](https://github.com/wutsi/wutsi-tenant-server)| ![](https://github.com/wutsi/wutsi-tenant-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-tenant-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-tenant-server/api/) - Supports for multi-tenancy |
|[Security](https://github.com/wutsi/wutsi-security-server)| ![](https://github.com/wutsi/wutsi-security-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-security-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-security-server/api/) - Manages authentication, authorization |
|[SMS](https://github.com/wutsi/wutsi-sms-server)| ![](https://github.com/wutsi/wutsi-sms-server/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-sms-sdk-kotlin) | [API](https://wutsi.github.io/wutsi-sms-server/api/) |
|[Analytics](https://console.firebase.google.com) |  | | Collects all the platform signals using [Google Firebase](https://console.firebase.google.com/) (Analytics, Crashlytics) |
| Monitoring |  | | Monitors the platform |
| Message Queue |  | | RabbitMQ as message bus |
| **Core Libraries** |
|[sdui](https://github.com/wutsi/sdui)| ![](https://github.com/wutsi/sdui/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/pub/v/sdui.svg) | Flutter Server Driven UI library |
|[sdui-kotlin](https://github.com/wutsi/sdui-kotlin)| ![](https://github.com/wutsi/sdui-kotlin/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/sdui-kotlin.svg) | Flutter Server Driven UI library |
|[wutsi-platform-payment](https://github.com/wutsi/wutsi-platform-payment)| ![](https://github.com/wutsi/wutsi-platform-payment/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-platform-payment) | Payment library for mobile payments (MTN, OM etc.) |
|[wutsi-platform-core](https://github.com/wutsi/wutsi-platform-core)| ![](https://github.com/wutsi/wutsi-platform-core/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-platform-core) | |
|[wutsi-openapi](https://github.com/wutsi/wutsi-openapi)| | | API in OpenAPI schemas |
|[wutsi-codegen](https://github.com/wutsi/wutsi-codegen)| ![](https://github.com/wutsi/wutsi-codegen/actions/workflows/master.yml/badge.svg) | ![](https://img.shields.io/github/v/tag/wutsi/wutsi-codegen) | OpenAPI to Kotlin code generateor |
| **Dev Tools** |
|[wutsi_devtools](https://github.com/wutsi/wutsi_devtools) | ![](https://github.com/wutsi/wutsi_devtools/actions/workflows/master.yml/badge.svg) |  | |

## Important Architectural Patterns
- [An Introduction to Micro Services](https://medium.com/microservicegeeks/an-introduction-to-microservices-a3a7e2297ee0)
- [The BFF Pattern (Backend for Frontend): An Introduction](https://blog.bitsrc.io/bff-pattern-backend-for-frontend-an-introduction-e4fa965128bf)
- [What is Server Driven UI](https://www.judo.app/blog/server-driven-ui/)

## Important Links
- Test Environment
  - [Analytics](https://console.firebase.google.com/u/0/project/wutsi-wallet-int/analytics/app/android:com.wutsi/overview/~2F%3Ft%3D1637862176262&fpn%3D4026312901&swu%3D1&sgu%3D1&sus%3Dupgraded&cs%3Dapp.m.dashboard.overview&g%3D1)
  - [Crashlytics](https://console.firebase.google.com/u/0/project/wutsi-wallet-int/crashlytics/app/android:com.wutsi/issues?state=open&time=last-seven-days&type=all&tag=all)

- Prod Environment
