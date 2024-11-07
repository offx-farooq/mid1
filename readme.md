# Abdullah Farooq
# 220996
## Overview
This project uses Docker Compose to run two services:

1. **MongoDB**: A NoSQL database to store application data.
2. **Cache Service**: A Redis cache to improve performance by storing frequently accessed data.

## Services

### 1. MongoDB Service
- **Purpose**: Stores the application's data in a flexible, schema-less format (NoSQL).
- **Technology**: MongoDB
- **Ports**: Exposes port `27017` for MongoDB connections.

### 2. Cache Service
- **Purpose**: Caches frequently accessed data to speed up retrieval.
- **Technology**: Redis
- **Ports**: Exposes port `6379`.

## Running the Services with Docker Compose

### Prerequisites
Ensure Docker and Docker Compose are installed on your system.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   cd Users\Public\Downloads\devopsproject
