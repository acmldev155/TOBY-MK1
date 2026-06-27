# TOBY-MK1 - Dispositivo Tático Offline 🇧🇷

<div align="center">

**Projeto 100% Open Source criado por Antony Cleiton, 12 anos**  
**ACML DEV 2026 | Natal, RN - Brasil**

[[Licença: CC BY-NC-SA 4.0](https://img.shields.io/badge/Licença-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[[Status: Em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow.svg)]()
[[Hardware: Dez/2026](https://img.shields.io/badge/Hardware-Dez%2F2026-blue.svg)]()

</div>

---

## ⚠️ AVISO DE DOCUMENTAÇÃO - LEIA PRIMEIRO

**ESTA DOCUMENTAÇÃO PODE CONTER ERROS. VERIFIQUE TUDO ANTES DE MONTAR.**  
**ACML DEV 2026 NÃO se responsabiliza por docs erradas, incêndios ou ferimentos.**  
**Feito por garoto de 12 anos. Espere erros. Monte por sua conta e risco.**

---

## 🚀 O que é o TOBY MK1?

**TOBY MK1** é um dispositivo portátil 100% offline que roda **TOBYOS V.1 PRO** no ESP32.

**Filosofia:** Sem internet, sem rastreamento, sem espião, sem nuvem. Só você e o hardware.

**Conceito Principal:** Interface touch. Botão power só pra LIGAR/DESLIGAR.

**Status atual:** Só planejamento. Montagem prevista para **Dezembro/2026**.

## 🎯 Objetivo Real

1. **Comunicação tática:** Enviar/receber texto via rádio 433MHz com teclado touch
2. **Navegação GPS:** Mostrar coordenadas com menu touch
3. **Log de dados:** Salvar logs GPS/rádio no cartão SD
4. **Privacidade primeiro:** Zero dependência de nuvem

## ⚙️ Hardware - BOM Final Real

| Componente | Modelo | Função | Detalhes |
| --- | --- | --- | --- |
| **MCU** | ESP32-WROOM-32 | Processador principal | WiFi/BT desligados |
| **Tela** | 2.8" TFT Touch ST7789 | Interface touch colorida | 240x320, SPI |
| **Touch** | Resistivo | Entrada do usuário | Caneta inclusa |
| **Armazenamento** | Slot MicroSD | Cartão SD | Embutido no módulo da tela |
| **GPS** | NEO-6M | Coordenadas offline | UART |
| **Rádio** | CC1101 433MHz | Transmissor de dados | SPI, não é FM música |
| **Energia** | Bateria 18650 | Alimentação | 3.7V 3000mAh |
| **Botão** | 1x Botão Power | LIGA/DESLIGA APENAS | Não usado pra navegar |

**NÃO INCLUI:** Módulo RTC, rádio FM, calculadora, teclado físico, múltiplos botões.

**Custo estimado:** R$ 250 - R$ 320 com TFT touch + SD.

## 📱 TOBYOS V.1 PRO - Interface Touch

**LIGAR:** Inicia → Menu touch aparece → Toca pra selecionar apps  
**DESLIGAR:** Segura botão power → Desliga

| App | Status | Descrição | Controle Touch |
| --- | --- | --- | --- |
| **🗺️ GPS** | Planejado | Mostra Lat/Lon/Alt/Velocidade | Toca ATUALIZAR, toca SALVAR pra log no SD |
| **📡 Rádio 433MHz** | Planejado | Teclado touch pra digitar msg | Toca ENVIAR, toca msg recebida pra ver |
| **🔋 Bateria** | Planejado | Voltagem + porcentagem | Sempre visível no canto |
| **💾 Gerenciador** | Planejado | Ver/apagar logs do SD | Toca arquivos pra abrir |
| **⌨️ Teclado** | Planejado | QWERTY na tela | Toca letras pra digitar |

**Método de Entrada:** Touchscreen completo. Botão power é SÓ pra ligar/desligar.  
**Sem teclado físico. Toda navegação via toque.**

## 🗺️ Roadmap

**Out-Nov/2026** - Comprar componentes  
**Dez/2026** - Montar + calibrar touch  
**Jan/2027** - Codar UI touch do TOBYOS  
**Fev/2027** - Testes de campo  

## ⚖️ Licença

**Creative Commons BY-NC-SA 4.0**  
**✅ Use/modifique/compartilhe** pra uso pessoal  
**❌ Venda/comercial/remova créditos/me processe**  

## ⚠️ AVISOS CRÍTICOS

1. **CALIBRAÇÃO TOUCH:** Touch resistivo precisa calibrar. Pode ser impreciso.
2. **CARTÃO SD:** Use FAT32. Máx 32GB. Cartão ruim corrompe dados.
3. **RISCO DE INCÊNDIO:** 18650 pode explodir. Use célula protegida.
4. **LEIS DE RÁDIO:** Transmitir 433MHz pode precisar licença. Veja leis locais. Uso ilegal = CRIME SEU.
5. **PRECISÃO GPS:** Erro de ±10m. Não confie pra aviação.
6. **TENHO 12 ANOS:** Docs podem estar erradas. Verifique pinagem antes de ligar.

**Este aparelho TEM entrada touch. VOCÊ PODE digitar e enviar mensagens via 433MHz.**

## 📞 Contato

**GitHub:** [@acmldev155](https://github.com/acmldev155)  
**Projeto:** ACML DEV 2026 | Natal, RN - Brasil

---

<div align="center">

**Hardware: Dez/2026 - TFT Touch + SD**  
**Documentação: Junho 2026 - Verifique antes de montar**

</div>
