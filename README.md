# 🚀 Quick Deploy EMQX

MQTT Broker deployment configuration using Docker Compose.

## Prerequisites

- Docker and Docker Compose installed
- SSL certificates (cert.pem and key.pem)
- Access to ports 1883, 8883, 8083, 8084, and 18083

## Configuration ⚙️

The setup includes:
- MQTT (1883)
- MQTTS (8883)
- WebSocket (8083)
- WSS (8084)
- Dashboard (18083)

## Quick Start 🚦

1. Set up environment variables in `default.env`
2. Place SSL certificates:
   - cert.pem
   - key.pem

3. Start the service:
```bash
docker-compose up -d
```

4. Access the dashboard:
   - URL: http://localhost:18083
   - Default credentials:
     - Username: admin
     - Password: public

## Environment Variables 🔧

Check `default.env` for configuration options:
- EMQX_NAME: Broker name
- EMQX_HOST: Host configuration
- EMQX_LOADED_PLUGINS: Enabled authentication plugins
- TZ: Timezone setting

### 📚 Automation Training & Resources

- 🛒 [Products & Services](http://racksync.com)
- 📖 [Training Courses](https://facebook.com/racksync)

### 👥 Community

- 🏘️ [Home Automation Thailand](https://www.facebook.com/groups/hathailand)
- 🛍️ [Home Automation Marketplace](https://www.facebook.com/groups/hatmarketplace)
- 💬 [Home Automation Thailand Discord](https://discord.gg/Wc5CwnWkp4) 

## 🏢 [RACKSYNC CO., LTD.](https://racksync.com)

RACKSYNC is a leading technology company specializing in Automation and Smart Solutions. We offer comprehensive services from consultation to implementation, covering both small-scale and enterprise-level projects. Our expert team provides professional system integration, installation, and monitoring services. As a full-service technology provider, we also develop customized Software as a Service (SaaS) solutions to meet diverse business needs.

📍 RACKSYNC COMPANY LIMITED \
🌏 Suratthani, Thailand 84000 \
📧 Email : devops@racksync.com \
📞 Tel : +66 85 880 8885 

[![Home Automation Thailand Discord](https://img.shields.io/discord/986181205504438345?style=for-the-badge)](https://discord.gg/Wc5CwnWkp4) [![Github](https://img.shields.io/github/followers/racksync?style=for-the-badge)](https://github.com/racksync) 
[![WebsiteStatus](https://img.shields.io/website?down_color=grey&down_message=Offline&style=for-the-badge&up_color=green&up_message=Online&url=https%3A%2F%2Fracksync.com)](https://racksync.com)



