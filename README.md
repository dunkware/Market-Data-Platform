# Trade-Feed-Platform

** Tired of building the same thing over again? This project is a set of maven modules that abstract market data and feeds into a common model and provides connectors into specific market feed providers including Polygon and ActiveTick. The scope of feed end points is not widely scoped starting with streaming reactive end points that allow subscriptions to 1 second quote snapshots. 

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
