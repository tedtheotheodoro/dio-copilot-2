# **DIO Travels – Copiloto Personalizado no Microsoft Copilot Studio**

Projeto realizado como parte do desafio do bootcamp da DIO, com o objetivo de criar um agente virtual personalizado no Microsoft Copilot Studio.

## Visão Geral

O **DIO Travels** é um agente conversacional voltado para auxiliar brasileiros em viagens internacionais, oferecendo informações sobre documentos, status de voos e orientações úteis de forma amigável.

- **Nome do agente:** DIO Travels  
- **Descrição:** Um guia virtual para viagens inesquecíveis, conectando viajantes a experiências autênticas com assistência personalizada.  
- **Estilo de resposta:** Clássico (sem GenAI ativado)  
- **Tema principal:** Viagens internacionais  

##  Funcionalidades Criadas

### 1. Tópico personalizado: **Flight Status**
- Gatilhos configurados com frases como:  
  `check flight status`, `is my flight on time`, `flight arrival time` etc.
- Uso de variáveis para capturar:
  - Número do voo (`FlightNumber`)
  - Data (`FlightDate`)
- Estrutura lógica com perguntas ao usuário e resposta esperada sobre o status do voo (simulado).

### 2. Personalização do agente
- Instruções para o agente agir como consultor de viagens com empatia e atenção personalizada.
- Introdução clara no campo de **Test your agent**.

## 📸 Capturas de Tela

| Visão Geral do Agente | Tópico "Flight Status" |
|-----------------------|------------------------|
| ![Overview]((https://github.com/tedtheotheodoro/dio-copilot-2/blob/main/overwiew.png)) | ![Flight Status]((https://github.com/tedtheotheodoro/dio-copilot-2/blob/main/flight-status.png)) |

| Variáveis Criadas | Configuração de AI |
|------------------|---------------------|
| ![Variables](https://github.com/tedtheotheodoro/dio-copilot-2/blob/main/variables.png) | ![AI Settings](https://github.com/tedtheotheodoro/dio-copilot-2/blob/main/ai-settings.png) |


## Conclusão

O desafio foi uma excelente introdução ao uso do Microsoft Copilot Studio, mostrando como estruturar um fluxo de conversa eficaz. O projeto pode evoluir com novos tópicos e ativação do GenAI para respostas mais fluidas e naturais.

---

Projeto desenvolvido por [Theodoro Fraga de Castro]((http://linkedin.com/in/theodoro-fraga-b3602332b/))
