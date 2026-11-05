# 📡 projeto-iot-esp32-mqtt

Projeto de **Internet das Coisas (IoT)** que usa um **ESP32** para coletar dados de sensores e enviá-los via **MQTT** para um broker, permitindo monitoramento e tratamento em tempo real.

---

## 📌 Sobre o projeto

Este projeto demonstra a comunicação entre um dispositivo embarcado e uma plataforma de dados usando o protocolo MQTT, no modelo **publish/subscribe**.

O ESP32 se conecta ao Wi-Fi, lê os dados do **potenciometro** e publica as leituras em tópicos de um broker MQTT. Outros clientes como **Node-RED / dashboard** assinam esses tópicos para receber, tratar e exibir as informações.

## 🛠️ Tecnologias e componentes

**Hardware**
- ESP32
- [Outros componentes: protoboard, jumpers, LED, relé etc.]

**Software**
- Node-RED
- Protocolo MQTT
- Broker: HiveMQ

**Bibliotecas**
- `WiFi.h`
- `PubSubClient`

## 📂 Estrutura do repositório

```
projeto-iot-esp32-mqtt/
├── projeto-iot-esp32-mqtt/   # Código-fonte do projeto
└── README.md
```

## 🔌 Ligações (circuito)

| Componente     | Pino do ESP32 |
|----------------|---------------|
| Led            | GPIO GND e 2  |
| Broker         | GPIO GND e 15 |
| Potenciometro  | GPIO GND e 15 |


## 👤 Autor

**Arthur Miguel Schlichting**
- GitHub: [@arthurSchgg](https://github.com/arthurSchgg)
