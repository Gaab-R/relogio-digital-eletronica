# ⏰ Relógio Digital com Circuitos Lógicos

Projeto de um relógio digital desenvolvido com eletrônica digital discreta, utilizando protoboard, jumpers e circuitos integrados (CIs), sem o uso de microcontroladores.

O projeto foi realizado com o objetivo de aplicar, na prática, conceitos de circuitos sequenciais, temporização, contagem e decodificação estudados em laboratório de Eletrônica Digital.

---

## 🎯 Objetivo
Desenvolver um relógio digital funcional capaz de realizar a contagem de segundos, minutos e horas, utilizando circuitos integrados lógicos, exibindo os valores em displays de sete segmentos.

---

## ⚙️ Visão geral do funcionamento
O sistema é dividido em blocos funcionais:

- *Geração de clock:*  
  Utilização de um CI 555 configurado no modo astável para geração de um sinal de 1 Hz (1 pulso por segundo).

- *Contagem sequencial:*  
  Contadores binários realizam a contagem de segundos, minutos e horas, com lógica adicional para reset automático nos valores máximos (59 segundos, 59 minutos e 23 horas).

- *Lógica de controle:*  
  Portas lógicas AND e OR são utilizadas para gerar os sinais de reset e propagação de contagem entre os estágios.

- *Decodificação e exibição:*  
  Os valores binários são convertidos para sinais compatíveis com displays de sete segmentos por meio de decodificadores BCD.

---

## 🔧 Principais componentes utilizados
- CI 555 – Gerador de clock
- SN74LS93N – Contadores binários
- SN74LS08N – Portas lógicas AND
- SN74LS32N – Portas lógicas OR
- CD4511 – Decodificador BCD para display de 7 segmentos
- Displays de 7 segmentos (cátodo comum)
- Protoboard, jumpers, resistores e capacitores

---

## 🎥 Demonstração
Vídeo do projeto funcionando:  
🔗 https://drive.google.com/file/d/1llMti3HTV9kcPDNxH_zyyDx4j1XdJNWo/view?usp=drivesdk

---

## 🧠 Aprendizados
- Eletrônica digital aplicada
- Circuitos sequenciais e temporização
- Leitura e interpretação de datasheets
- Montagem e depuração de circuitos em protoboard
- Organização lógica de sistemas digitais

---

## 📚 Contexto acadêmico
Projeto desenvolvido no laboratório de Eletrônica Digital do curso de Engenharia da Computação – Centro Universitário Fundação Santo André.
