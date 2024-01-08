## 🎵 MelodyBay: Copyright-free Music Sharing Platform with Microservices
MelodyBay is a copyright-free music-sharing platform designed to provide a wide range of features for music lovers and artists. Our platform emphasizes effortless sharing, discovering, and appreciating copyright-free music.

### 🌟 Features
Users can
  - Listen, download, and search for songs.
  - Create and manage playlists.
  - Add songs to favorites.
  - Share songs with friends.
  - Get personalized song recommendations.
  - User account management for registration and login.
  - Become an artist to upload songs.

### 🔍 Services
- Discovery service: Responsible for a service registry monitoring the heartbeat of all servers using Eureka.
- Feign service: Responsible for HTTP requests between servers via Feign API.
- Gateways service: Responsible for routing requests using Spring Gateway.
- User service: Manage user information and roles, and support artist profiles and bands using MySQL and JPA.
- Media service: Handles all images, videos, and music files; responsible for uploading files to MinIO and sending information to the music library with MySQL, MinIO, JPA, and RabbitMQ.
- Music library service: Stores all music information using MySQL, and users can use this service to query for specific music; Use RabbitMQ for music information updates.
- Playlist service: Responsible for collecting playlist songs using JPA and MySQL.
- Listen history service: Responsible for the history of the music the user listened to using MongoDB.
- Elasticsearch service: Responsible for quickly searching for words entered by the user, including prefixes and fuzzy searches, as well as saving basic display information for album, track, and artist.
- Recommendations service: Responsible for music recommendations based on user behavior and trends.
- Authentication service: Validates user login and registration information, and tokens operations using MySQL, JPA, Spring Security, OAuth2, and JWT.

### 🛠 Technologies
#### 💻 Frontend
- TypeScript
- React
- Material UI

#### 🖥 Backend
- Java
- Spring Boot
- Spring Cloud
- MySQL
- Hibernate
- Elasticsearch
- Eruka
- RabbitMQ
- MinIO
- Redis
- Spring Gateway
- Load Balancing
- OAuth 2 Authentication
