# Minecraft APIs Documentation

This documentation provides an overview and usage examples of the Minecraft APIs endpoints.

## Base URL

The base URL for all API endpoints is `https://mc.ap1.pw/`.


## Endpoints

### 1. Server Status (`/status`)
- **Method:** GET
- **Description:** Returns the status of a Minecraft server including version, player count, MOTD, and more.
- **Query Parameters:**
  - `address`: The IP address or hostname of the Minecraft server (required).
  - `port`: The port on which the Minecraft server is running (default: 25565).

### 2. Server Icon (`/icon`)
- **Method:** GET
- **Description:** Retrieves the server's icon if available.
- **Query Parameters:**
  - `address`: The IP address or hostname of the Minecraft server (required).
  - `port`: The port on which the Minecraft server is running (default: 25565).

### 3. Player Information (`/player`)
- **Method:** GET
- **Description:** Fetches player information by username or UUID.
- **Query Parameters:**
  - `username`: The player's username.
  - `uuid`: The player's UUID.

### 4. Player Head (`/player/head`)
- **Method:** GET
- **Description:** Returns a player's head image based on their UUID or username.
- **Query Parameters:**
  - `uuid`: The player's UUID.
  - `username`: The player's username.

### 5. Player Skin (`/player/skin`)
- **Method:** GET
- **Description:** Retrieves the player's skin.
- **Query Parameters:**
  - `username`: The player's username (required).

## A AP1 Project

This project was made by AP1 and is managed by AP1.
