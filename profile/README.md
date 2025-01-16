# tnfy.link

[![GitHub license](https://img.shields.io/github/license/tnfy-link/backend)](https://github.com/tnfy-link/.github/blob/master/LICENSE)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Ftnfy.link)](https://tnfy.link)

- [tnfy.link](#tnfylink)
  - [🌐 Usage](#-usage)
  - [🚀 Features](#-features)
  - [🛠 Tech Stack](#-tech-stack)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)

A high-performance URL shortener service built with Go, using modern technologies and best practices. This service provides fast and reliable URL shortening capabilities with Redis-based storage.

## 🌐 Usage

The tnfy.link service can be accessed in two ways:

1. **Web Interface**: Visit [tnfy.link](https://tnfy.link) to use the service through our user-friendly web interface.
2. **API**: Access the service programmatically via our API at [api.tnfy.link](https://api.tnfy.link/v1/docs).

## 🚀 Features

- **High Performance**: Built with Go and Fiber framework for maximum speed
- **Statistics**: UTM labels support for analytics
- **Redis Storage**: Fast and reliable link storage with configurable TTL
- **Base58 Encoding**: Human-friendly short URLs using Base58 encoding
- **Docker Support**: Easy deployment with Docker and Docker Compose
- **Configurable**: Environment-based configuration for flexibility
- **Structured Logging**: Comprehensive logging with Zap logger
- **Dependency Injection**: Clean architecture using Uber's fx framework

## 🛠 Tech Stack

- **Language**: Go 1.23+
- **Web Framework**: [Fiber v2](https://github.com/gofiber/fiber)
- **Storage**: Redis
- **Logging**: Uber Zap
- **DI Framework**: Uber fx
- **Containerization**: Docker

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

---
Built with ❤️ using Go and [Codeium](https://codeium.com).
