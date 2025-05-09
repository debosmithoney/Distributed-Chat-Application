```
chat-app/
│
├── api-gateway/
│   ├── src/main/java/com/chat/gateway/
│   │   ├── GatewayApplication.java
│   │   ├── SecurityConfig.java
│   ├── Dockerfile
│
├── auth-service/
│   ├── src/main/java/com/chat/auth/
│   │   ├── AuthApplication.java
│   │   ├── controller/AuthController.java
│   │   ├── service/AuthService.java
│   ├── Dockerfile
│
├── chat-service/
│   ├── src/main/java/com/chat/chat/
│   │   ├── ChatApplication.java
│   │   ├── controller/ChatController.java
│   │   ├── service/ChatService.java
│   │   ├── util/AESUtil.java
│   ├── Dockerfile
│
├── user-service/
│   ├── src/main/java/com/chat/user/
│   │   ├── UserApplication.java
│   │   ├── controller/UserController.java
│   │   ├── service/UserService.java
│   ├── Dockerfile
│
├── notification-service/
│   ├── src/main/java/com/chat/notification/
│   │   ├── NotificationApplication.java
│   │   ├── controller/NotificationController.java
│   ├── Dockerfile
│
├── encryption-service/
│   ├── src/main/java/com/chat/encryption/
│   │   ├── EncryptionApplication.java
│   │   ├── util/RSAUtil.java
│   ├── Dockerfile
│
└── docker-compose.yml
```
