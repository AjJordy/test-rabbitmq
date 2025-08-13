# Test RabbitMQ

### Dependences

- UV 
- Docker compose

### Test

```bash
docker compose up -d
uv run src/consumer.py
uv run src/producer.py
```