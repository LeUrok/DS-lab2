### Cars Service 8070:
```
GET /manage/health
GET /api/v1/cars?page&size&showAll
GET /api/v1/cars/{carUid}
POST /api/v1/cars/{carUid}/reserve
POST /api/v1/cars/{carUid}/unreserve
```
---
### Rental Service 8060:

```
GET /manage/health
GET /api/v1/rental?username=<u> 
GET /api/v1/rental/{rentalUid}
POST /api/v1/rental 
POST /api/v1/rental/{rentalUid}/finish
DELETE /api/v1/rental/{rentalUid}
```
---
### Payment Service 8050:
```
GET /manage/health
POST /api/v1/payment 
GET /api/v1/payment/{paymentUid}
DELETE /api/v1/payment/{paymentUid} 
```
