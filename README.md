# Market Data Platform
** Complete market data package that provides an abstract market data and feed model with streaming http using reactive libs and market feed provider integrations with ActiveTick and Polygon Providers. The API is scope at a common generic abstract model as well as provider specific end points that don't map to a common model. Have Fun. 

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
