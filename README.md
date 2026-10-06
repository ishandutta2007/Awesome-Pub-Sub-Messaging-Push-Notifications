# Awesome-Pub-Sub-Messaging-Push-Notifications

## Top Pub/Sub Messaging & Push Notifications Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Real-Time Messaging, Multi-Channel Notifications & Self-Hosted Pub/Sub*  

**Last updated: October 2026**



This repository tracks notable **commercial pub/sub and push notification platforms** and **open-source projects** that deliver real-time messages across web, mobile, email, SMS, and chat channels — from simple push notifications to sophisticated notification infrastructure with workflows and preferences.



**Examples** include Amazon SNS, Firebase Cloud Messaging, OneSignal, Twilio, Pusher, Novu, Knock, Courier, Airship, and Braze (the category leaders).



**Open-source emphasis**: Pub/sub messaging and notifications are strong open-source domains. **Novu** leads as the most comprehensive open-source notification infrastructure. **ntfy**, **Gotify**, and **Apprise** deliver self-hosted push notifications. **Centrifugo** and **Mercure** power real-time pub/sub messaging. **NATS**, **Redis Pub/Sub**, and **Apache Pulsar** provide messaging backbones. **web-push** and **pywebpush** handle browser push. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon SNS](https://aws.amazon.com/sns/)**  

  **AWS's pub/sub messaging service** — topics, subscriptions, and mobile push . **SMS, email, SQS, and Lambda delivery** . **Best for AWS-native pub/sub** .



- **[Firebase Cloud Messaging](https://firebase.google.com/products/cloud-messaging)**  

  **Google's push notification service** — cross-platform messaging for mobile and web . **Best for Firebase ecosystem** .



- **[OneSignal](https://onesignal.com/)**  

  **The leading push notification platform** — mobile, web, and email notifications . **Best for mobile engagement** .



- **[Twilio](https://www.twilio.com/)**  

  **Communication APIs** — SMS, voice, email, and push notifications . **Best for omnichannel communication** .



- **[Pusher](https://pusher.com/)**  

  **Real-time pub/sub messaging** — WebSocket-based channels for applications . **Best for real-time features** .



- **[Novu](https://novu.co/)**  

  **Open-source notification infrastructure** — see Open-Source section for self-hosted option.



- **[Knock](https://knock.app/)**  

  **Notification infrastructure** — workflow builder and subscriber preferences . **Best for developer-friendly notifications** .



- **[Courier](https://www.courier.com/)**  

  **Notification infrastructure API** — route messages across email, SMS, push, and chat . **Best for multi-channel notifications** .



- **[Airship](https://www.airship.com/)**  

  **Customer engagement platform** — push, in-app, SMS, and email . **Best for enterprise engagement** .



- **[Braze](https://www.braze.com/)**  

  **Customer engagement platform** — cross-channel messaging and analytics . **Best for enterprise marketing** .



## Open-Source GitHub Projects



### Notification Infrastructure



- **[Novu](https://github.com/novuhq/novu)**  

  **The leading open-source notification infrastructure platform**, MIT licensed with **35,000+ GitHub stars** . **Unified API for email, SMS, push, in-app inbox, Slack, Teams, Discord, and WhatsApp** . **Visual workflow editor** with drag-and-drop flow builder, conditions, delays, and digest . **In-app notification center** (embeddable React/Angular/Vue inbox) . **Subscriber preference management** and template editor with i18n . **No per-notification pricing** — pay only for compute . **The de facto open-source Courier and Knock alternative** . **Best for comprehensive notification infrastructure** .



- **[Apprise](https://github.com/caronc/apprise)**  

  **Push notification library for 100+ services**, MIT licensed with **12,000+ GitHub stars** . **One API for Discord, Slack, Telegram, email, SMS, and more** . **CLI and Python library** . **Best for multi-service notifications** .



- **[ntfy](https://github.com/binwiederhier/ntfy)**  

  **Simple HTTP-based pub/sub notification service**, Apache-2.0/GPL-2.0 licensed with **20,000+ GitHub stars** . **Send notifications via HTTP PUT/POST** . **Subscribe via web, Android, iOS, or CLI** . **Self-hosted with no account required** . **The simplest self-hosted push notification service** . **Best for simple, self-hosted notifications** .



- **[Gotify](https://github.com/gotify/server)**  

  **Self-hosted push notification server**, MIT licensed with **10,000+ GitHub stars** . **Simple REST API for sending messages** . **Web UI and Android app** . **Best for self-hosted push notifications** .



- **[Notifuse](https://github.com/Notifuse/notifuse)** — Open-source notification infrastructure .



### Pub/Sub Messaging Platforms



- **[Centrifugo](https://github.com/centrifugal/centrifugo)**  

  **Scalable real-time messaging server**, Apache-2.0 licensed with **8,000+ GitHub stars** . **WebSocket, HTTP-streaming, SSE, and GRPC** . **Pub/sub channels with presence and history** . **Best for real-time pub/sub** .



- **[Mercure](https://github.com/dunglas/mercure)**  

  **Open-source protocol for real-time updates**, AGPL-3.0 licensed . **Server-sent events (SSE) based** . **Best for real-time web updates** .



- **[NATS](https://github.com/nats-io/nats-server)**  

  **Cloud-native messaging system**, Apache-2.0 licensed . **Lightweight, high-performance pub/sub** with JetStream for persistence . **Best for IoT and edge pub/sub** .



- **[Redis Pub/Sub](https://github.com/redis/redis)**  

  **In-memory pub/sub messaging**, BSD-3-Clause licensed . **Simple channel-based messaging** . **Best for simple pub/sub** .



- **[Apache Pulsar](https://github.com/apache/pulsar)**  

  **Distributed messaging and streaming platform**, Apache-2.0 licensed with **14,000+ GitHub stars** . **Multi-tenancy, geo-replication, and tiered storage** . **Best for multi-tenant pub/sub** .



- **[Apache Kafka](https://github.com/apache/kafka)**  

  **Event streaming platform**, Apache-2.0 licensed with **28,000+ GitHub stars** . **Distributed pub/sub with persistence** . **Best for high-throughput pub/sub** .



- **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)**  

  **Message broker with pub/sub support**, MPL-2.0 licensed with **12,000+ GitHub stars** . **AMQP, MQTT, and STOMP support** . **Best for reliable messaging** .



### Push Notification Libraries



- **[web-push](https://github.com/web-push-libs/web-push)**  

  **Web Push library for Node.js**, MIT licensed with **3,000+ GitHub stars** . **Send push notifications to browsers** . **Best for web push** .



- **[pywebpush](https://github.com/web-push-libs/pywebpush)**  

  **Web Push library for Python**, MPL-2.0 licensed . **Send push notifications to browsers** . **Best for Python web push** .



- **[PushSharp](https://github.com/Redth/PushSharp)** — .NET push notification library (archived) .



- **[node-gcm](https://github.com/ToothlessGear/node-gcm)** — Google Cloud Messaging library for Node.js (deprecated) .



### MQTT & IoT Messaging



- **[Mosquitto](https://github.com/eclipse/mosquitto)**  

  **The standard open-source MQTT broker**, EPL-2.0 licensed . **Lightweight and efficient** . **Best for IoT messaging** .



- **[EMQX](https://github.com/emqx/emqx)**  

  **High-performance MQTT broker**, Apache-2.0 licensed with **13,000+ GitHub stars** . **Scalable to 100M+ connections** . **Best for large-scale IoT messaging** .



- **[VerneMQ](https://github.com/vernemq/vernemq)**  

  **Distributed MQTT broker**, Apache-2.0 licensed . **Scalable and fault-tolerant** . **Best for clustered MQTT** .



- **[NanoMQ](https://github.com/nanomq/nanomq)**  

  **Lightweight MQTT broker for edge**, MIT licensed . **Best for edge MQTT** .



### Additional Strong Open-Source Options



- **Novu** — Complete notification infrastructure .

- **ntfy** — Simple HTTP-based push .

- **Gotify** — Self-hosted push .

- **Apprise** — Multi-service notifications .

- **Centrifugo** — Real-time pub/sub .

- **Mercure** — SSE-based pub/sub .

- **NATS** — Cloud-native messaging .

- **Redis Pub/Sub** — In-memory pub/sub .

- **Apache Pulsar** — Multi-tenant pub/sub .

- **RabbitMQ** — Reliable messaging .

- **Mosquitto** — MQTT broker .

- **EMQX** — Scalable MQTT .

- **web-push** — Web push library .

- **pywebpush** — Python web push .



**Frameworks for building custom pub/sub and notification solutions**: Combine **Novu** for comprehensive notification infrastructure with multi-channel support . Use **ntfy** or **Gotify** for simple self-hosted push notifications . Deploy **Centrifugo** or **Mercure** for real-time pub/sub messaging . Choose **NATS** for cloud-native messaging . Integrate **Apprise** for multi-service notification routing . Use **web-push** for browser push notifications . Deploy **Mosquitto** or **EMQX** for MQTT-based IoT messaging . Note that true managed notification services with global delivery, delivery analytics, and vendor-supported SLAs (OneSignal, Courier, Knock, Braze) remain primarily commercial territory; open-source stacks provide strong notification infrastructure, pub/sub messaging, and push delivery foundations that require integration for complete multi-channel notifications.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Pub/sub and notification platforms handle user data and communication preferences. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, CAN-SPAM).

- **Push notification delivery depends on platform providers** — APNs (Apple) and FCM (Google) mediate mobile push. Self-hosted notification platforms still require these services for mobile delivery .

- **Email deliverability requires IP reputation management** — self-hosted email notifications must warm up IPs, configure SPF/DKIM/DMARC, and monitor blacklists .

- **License considerations**: Novu uses MIT, ntfy uses Apache-2.0/GPL-2.0, Centrifugo uses Apache-2.0, and Mercure uses AGPL-3.0. Verify licensing against your use case before committing .

- The open-source ecosystem provides strong notification infrastructure, pub/sub messaging, and push delivery foundations, but **global delivery, delivery analytics, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for developers, platform engineers, and organizations seeking notification sovereignty.**  

Let's make pub/sub messaging and push notifications more open, transparent, and reliable.
