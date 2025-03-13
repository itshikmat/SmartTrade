# SmartTrade API Documentation

## Base URL
`https://api.smarttrade.io/v1/`

## Endpoints
### 1. Get User Profile
`GET /users/{user_id}`  
**Response:**
```json
{
  "id": 123,
  "username": "trader123",
  "reputation": 95
}
```
### 2. Create a Trade Listing
`POST /listings/create`  
**Payload:**
```json
{
  "title": "Selling 10 BTC",
  "price": 45000,
  "currency": "USD"
}
```
