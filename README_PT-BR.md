# TOBY-MK1 - TOBYOS V.1 PRO Dispositivo Tático 🇧🇷

<div align="center">

**100% Open Source | TOBYOS V.1 PRO | ESP32**  
**Criado por Antony Cleiton, 12 anos**  
**ACML DEV 2026 | Natal, RN - Brasil**

[[Licença: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licença-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[[Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow.svg)]()
[[Hardware: Dez/2026](https://img.shields.io/badge/Hardware-Dez%2F2026-blue.svg)]()

</div>

---

## ⚠️ AVISO DE DOCUMENTAÇÃO

**ESTA DOCUMENTAÇÃO PODE CONTER ERROS. TENHO 12 ANOS.**  
**VERIFIQUE TODOS OS ESQUEMAS, CÓDIGOS E PINAGENS ANTES DE MONTAR.**  
**ACML DEV 2026 NÃO SE RESPONSABILIZA POR INCÊNDIOS, FERIMENTOS OU SONHOS QUEBRADOS.**  
**MONTE POR SUA CONTA E RISCO.**

---

## 🚀 O que é o TOBY MK1?

**TOBY MK1** roda **TOBYOS V.1 PRO** - sistema operacional tático offline no ESP32.

**Filosofia:** Computador de bolso. Sem internet. Sem nuvem. Sem rastreamento. Só hardware.

**Status Hardware:** Fase de planejamento. Montagem física prevista para **Dezembro/2026**.

## ⚙️ Hardware - BOM Real

| Componente | Modelo | Função no TOBYOS |
| --- | --- | --- |
| **MCU** | ESP32-WROOM-32 | Roda TOBYOS + WiFi + BT + SPI |
| **Tela** | 2.8" TFT Touch ST7789 | 240x320 Touch UI + Teclado Virtual |
| **Armazenamento** | Slot MicroSD | Embutido no módulo TFT. Sistema de arquivos TOBYOS |
| **GPS** | NEO-6M | App GPS - Coordenadas + log GPX |
| **Rádio** | CC1101 433MHz | App RF Scanner - Detecta sinais 433MHz |
| **IR** | LED IR + Receptor | App IR - Clonar/controlar TV, ar-condicionado |
| **Energia** | 18650 3.7V | Bateria principal |
| **Botão** | 1x Power | LIGA/DESLIGA APENAS. NÃO controla apps |

**NÃO INCLUI:** RTC, rádio FM, calculadora, teclado físico.  
**Custo Estimado:** R$ 280 - R$ 350

## 📱 TOBYOS V.1 PRO - 8 Apps Independentes

Todos os apps funcionam sozinhos via touchscreen. Nenhum app depende de outro.

| App | Ícone | Função |
| --- | --- | --- |
| **Configurações** | ⚙️ | Ajusta brilho, som, calibração touch, senha WiFi AP |
| **Wi-Fi** | 📶 | Scan redes 2.4GHz, modo AP, info pacotes |
| **Bluetooth** | 📡 | Scanner BLE, detecta beacons, RSSI |
| **IR Remote** | 📺 | Grava/envia códigos IR. Controla TV, AC |
| **RF Scanner** | 📻 | CC1101 433MHz. Detecta controles, sensores. NÃO é chat |
| **GPS Tracker** | 🗺️ | Lat/Lon/Alt/Vel. Salva logs GPX no SD |
| **SCFTOS** | 📡 | SiteControlForTobyOS - Controle remoto opcional via celular |
| **Bootloader** | 🔄 | Atualiza firmware TOBYOS via SD ou WiFi OTA |

**SCFTOS é OPCIONAL.** Aparelho funciona 100% sem celular. SCFTOS só deixa controlar/baixar via navegador.

## 📖 MANUAL DO USUÁRIO - Como Usar o TOBY MK1

### **1. Ligar/Desligar**
- **LIGAR:** Segura botão power 2 segundos → TOBYOS inicia
- **DESLIGAR:** Segura botão power 3 segundos → Desliga
- **Botão power NÃO FAZ MAIS NADA.** Todo controle é na tela touch.

### **2. Navegação Menu Principal**
Após ligar, você vê 8 ícones de apps. **Toque em qualquer ícone para abrir.**
