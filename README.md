# mini-broadcast-service

A scaled-down LINE-style broadcast system for practicing high-concurrency backend design.

Goal: send a campaign to 1M recipients through RabbitMQ and async Python workers, with Redis rate limiting and dedup, no lost and no duplicate messages, and measured load-test numbers.

Stack: FastAPI, PostgreSQL, RabbitMQ, Redis, Prometheus / Grafana, k6.
