# TOBY-MK1 - Dispositivo Tático Offline 🇧🇷

<div align="center">

**Projeto 100% Open Source criado por Antony Cleiton, 12 anos**  
**ACML DEV 2026 | Natal, RN - Brasil**

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow.svg)]()
[![Hardware: Dez/2026](https://img.shields.io/badge/Hardware-Dez%2F2026-blue.svg)]()

</div>

---

## 🚀 O que é o TOBY MK1?

O **TOBY MK1** é um dispositivo portátil 100% offline que roda o sistema **TOBYOS V.1 PRO** no ESP32. 

**Filosofia:** Sem internet, sem rastreamento, sem espião, sem nuvem. Só você e o hardware.

**Status atual:** Planejamento e documentação. Montagem do hardware prevista para **Dezembro/2026**.

## 🎯 Objetivo do Projeto

Criar um dispositivo pessoal que serve como:
1. **Ferramenta de sobrevivência** com GPS offline, rádio FM e bússola
2. **Plataforma de aprendizado** para eletrônica e programação embarcada
3. **Prova de conceito** que um garoto de 12 anos pode criar tecnologia de ponta

## ⚙️ Hardware Planejado - BOM Completa

| Categoria | Componente | Modelo | Função no TOBYOS |
| --- | --- | --- | --- |
| **Processador** | ESP32-WROOM-32 | 240MHz Dual Core | Cérebro principal do sistema |
| **Tela** | OLED SSD1306 | 128x64 I2C | Interface gráfica |
| **Entrada** | Teclado Mecânico 3D | Custom 4x4 Matrix | Digitação e navegação |
| **Tempo Real** | RTC DS3231 | I2C com bateria | Relógio e calendário offline |
| **Localização** | GPS NEO-6M | UART | GPS offline sem internet |
| **Rádio** | TEA5767 | FM I2C | Rádio FM 76-108MHz |
| **Sensores** | MPU6050 | Acel + Giroscópio | Bússola e movimento |
| **Armazenamento** | Cartão SD | SPI até 32GB | Mapas, músicas, notas |
| **Energia** | Bateria 18650 | 3.7V 3000mAh | Autonomia portátil |
| **Carregamento** | TP4056 | USB-C | Carregador seguro |

**Custo estimado:** R$ 180 - R$ 250

## 📱 Apps do TOBYOS V.1 PRO

| App | Status | Descrição |
| --- | --- | --- |
| **🕐 Relógio** | Planejado | Horário com RTC DS3231 + alarme |
| **🗺️ GPS Offline** | Planejado | Mapas OpenStreetMap no SD |
| **📻 Rádio FM** | Planejado | TEA5767 com memória de estações |
| **🧮 Calculadora** | Planejado | Operações básicas + científicas |
| **📝 Notas** | Planejado | Editor de texto salvo no SD |
| **🧭 Bússola** | Planejado | MPU6050 com calibração |
| **⚙️ Config** | Planejado | Brilho, som, info do sistema |
| **🔋 Bateria** | Planejado | Monitor de voltagem 18650 |

## 🗺️ Roadmap - Dez/2026

**Fase 1: Out-Nov/2026** - Compra dos componentes  
**Fase 2: Dez/2026** - Montagem do hardware e soldas  
**Fase 3: Jan/2027** - Código do TOBYOS V.1 PRO  
**Fase 4: Fev/2027** - Testes e vídeos de demonstração  

## ⚖️ Licença - LEIA ISSO

Este projeto usa **Creative Commons BY-NC-SA 4.0**.

### ✅ Você PODE:
- Montar seu próprio TOBY MK1 pra uso pessoal
- Estudar o código e esquemas
- Modificar e melhorar o projeto
- Compartilhar suas melhorias com a comunidade

### ❌ Você NÃO PODE:
- **Vender o TOBY MK1** ou qualquer derivado
- Usar em produto comercial
- Remover os créditos do Antony Cleiton
- Fechar o código das suas modificações

**Resumo:** Use, aprenda, melhore, compartilhe. Só não lucre em cima.

## ⚠️ Aviso Legal Importante

**Este projeto foi criado por um menor de idade de 12 anos para fins educacionais.**

**ACML DEV 2026 e Antony Cleiton NÃO se responsabilizam por:**
- Danos causados por montagem incorreta
- Curto-circuito, explosão de bateria ou incêndio
- Lesões durante soldagem ou uso
- Perda de dados ou mau funcionamento
- Uso indevido do dispositivo

**Ao montar ou usar este projeto, você concorda que faz por sua conta e risco.**  
**Não processe um garoto de 12 anos.**

## 🤝 Como Contribuir

1. **Dê uma estrela ⭐** no repo se curtiu
2. **Abra uma Issue** pra sugerir melhorias
3. **Faça um Fork** e mande Pull Request
4. **Compartilhe** com quem curte eletrônica

## 📞 Contato

**GitHub:** [@acmldev155](https://github.com/acmldev155)  
**Projeto:** ACML DEV 2026  
**Local:** Natal, RN - Brasil

---

<div align="center">

**Hardware build scheduled for Dec/2026**  
*Documentação será atualizada conforme o projeto evolui*

**TOBY MK1 - Tecnologia brasileira, código aberto, futuro offline.**

</div>
