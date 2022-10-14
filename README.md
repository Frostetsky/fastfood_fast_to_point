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

ecosystem-vault-service - сервис хранения secret-ов

ecosystem-config-service - сервис конфигурации

ecosystem-discovery-service - сервис обнаружения

Дополнительно в проекте используется Apache Kafka для обмена данными между сервисами.

Для работы с сессиями и кешами используется Redis.

Продакшен мод подразумевает использование до 4-ёх инстансов основных сервисов и распределение нагрузки
между ними.

