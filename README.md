ecosystem-admin-service - сервис администратора (верхнеуровневый сервис)

ecosystem-dish-service - сервис блюд

ecosystem-order-service - сервис заказов

ecosystem-delivery-service - сервис доставки

ecosystem-kitchen-service - сервис кухни

ecosystem-payment-service - сервис платежей

ecosystem-notification-service - сервис уведомлений

ecosystem-common - доменные модели

ecosystem-authorization-service - сервис авторизации (OAuth 2.0)

ecosystem-api-gateway-service - единый шлюз входа

ecosystem-vault-service - сервис хранени€ secret-ов

ecosystem-config-service - сервис конфигурации

ecosystem-discovery-service - сервис обнаружени€

ƒополнительно в проекте используетс€ Apache Kafka дл€ обмена данными между сервисами
ƒл€ работы с сесси€ми и кешами используетс€ Redis

ѕродакшен мод подразумевает использование до 4-Єх инстансов основных сервисов и распределение нагрузки
между ними

