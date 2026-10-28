# İNÜ Öğrenci Toplulukları Envanter Yönetim Sistemi

Klasörler: `frontend/` (Flutter Web), `backend/` (Spring Boot, Java 21), `docker-compose.yml`.

## Çalıştırma
```
docker compose up --build -d
```

| Servis | Adres |
|---|---|
| Frontend | http://localhost:3000 |
| Backend health | http://localhost:8080/api/health |
| Swagger UI | http://localhost:8080/swagger-ui.html |
| pgAdmin | http://localhost:5050 (admin@inu.edu.tr / admin) |
| PostgreSQL | localhost:5432 (inu / inu_secret, db: inu_inventory) |

Ayarları değiştirmek için `.env.example` dosyasını `.env` olarak kopyalayın.

