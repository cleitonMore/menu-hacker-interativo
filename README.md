# menu-hacker-interativo

<h1 align="center">⚡ ESP8266 - Menu Interativo Hacker com OLED e Digispark ⚡</h1>

<p align="center">
  Interface embarcada para projetos de <b>cibersegurança ofensiva/defensiva</b> com ESP8266, OLED e Digispark.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-C++-blue?logo=arduino" />
  <img src="https://img.shields.io/badge/Hardware-ESP8266-green" />
  <img src="https://img.shields.io/badge/Digispark-Serial-red" />
  <img src="https://img.shields.io/badge/OLED-128x64-yellow" />
</p>

---

## 📌 Visão Geral

Este projeto é um sistema embarcado que:

- Exibe **um menu interativo na tela OLED** com animações
- Permite navegação por **botões físicos**
- Realiza **escaneamento de redes Wi-Fi**
- **Clona redes** selecionadas (modo Evil Twin)
- Envia comandos para o **Digispark**, acionando ações ofensivas (HID attacks, payloads etc.)
- Inclui um modo animado estilo **Matrix caindo** na tela OLED

---

## 🧰 Tecnologias e Componentes

| Componente     | Função                                        |
|----------------|-----------------------------------------------|
| ESP8266        | Controlador principal                         |
| Display OLED   | Interface de exibição 128x64 (I2C)            |
| Botões físicos | Navegação no menu                             |
| Digispark      | Execução de payloads via comunicação serial   |
| Linguagem      | C++ com Arduino Framework                     |

---

## 🚀 Funcionalidades

- Menu interativo com múltiplas opções
- Tela inicial estilizada e “modo Matrix”
- Escaneia redes Wi-Fi próximas
- Permite clonar SSIDs selecionados
- Comunicação com Digispark para ações externas
- Visual hacker 🔥

---

## 🎮 Interface

```plaintext
> ESCANEAR REDES
  CLONAR REDE
  MODO MATRIX
  ATAQUE (DIGISPARK)
