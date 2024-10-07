# ActiveTick-Spring-Boot

**ActiveTick-Spring-Boot** is a Spring Boot service that wraps the ActiveTick REST API, managing session token refreshes and providing a set of reactive API calls. This project is focused on streaming snapshot quotes for subscribed tickers at 1-second intervals, fulfilling requirements for high-frequency trading technology.

## Features
- **Session Management**: Automatically refreshes session tokens to keep your connection active for continuous data requests.
- **Reactive API Calls**: Offers an easy-to-use interface for retrieving snapshot quotes in real time.
- **Focus on Streaming**: Version 1.0.0 is optimized for streaming 1-second interval snapshot quotes, suitable for trading and financial analysis platforms.

## Getting Started
To get started, ensure you have **JDK 17+** installed.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Dunkware/ActiveTick-Spring-Boot.git
   cd ActiveTick-Spring-Boot
