# global_solution---computer_science
Mission Control AI...
GS2026 - 1CCPO

Equipe:      
Ana Julia Yumi Inoue - RM: 569430

João Pedro Santos Ferreira - RM: 569202

Maria Fernanda Dias Ribeiro - RM: 569999  

Objetivos: Mission Control AI propõe o desenvolvimento de um sistema inteligente de monitoramento e alerta para uma missão espacial experimental. Nosso projeto possui uma aplicação prática de conceitos de lógica digital, expressões booleanas e circuitos lógicos.  

Explicação do funcionamento do sistema de alerta - MISSION CONTROL AI 

Simulação realizada no TinkerCad.
Diagrama / circuito lógico feito no Logisim.
Tabela verdade feita no Google Planilhas.

Como funciona?           
- A lógica é simples, existem 7 variáveis, representadas por letras na ordem alfabética.       
- As variáveis A e B formam o primeiro AND, as variáveis C e D foram o segundo AND, e por sua vez, as variáveis E e F formam o terceiro e     último AND. E também existe o NOT que seria a variável G.       
- Os ANDs 1 e 2 vão para um OR auxiliar e o AND 3 e o NOT vão para um segundo OR auxiliar.      
  Depois, os ORs auxiliares se conectam a um OR principal que é diretamente conectado ao ALERTA, que seria o resultado da equação, o X.    
- Nosso X precisa resultar em 1, para isso, os ORs auxiliares são acionados; no primeiro caso, se qualquer um dos ANDs for acionado (1 ou 2), o OR é verdadeiro.         
  No segundo caso, se ou AND ou NOT for acionado, o segundo OR se torna verdadeiro. 
- No OR principal é mais simples, se qualquer um dos ORs auxiliares forem verdadeiros, o OR principal se torna verdadeiro, acionando o alarme (x).      
Resumindo, a lógica é: se qualquer problema/falha (variáveis) for detectado (verdadeiro), o alarme é acionado.        


Simulação no Tinkercad (link de acesso): https://www.tinkercad.com/things/2WXvJbMPA61-gs-computer-science?sharecode=zIMbc8yWQ_uzuldJ8IseZDQyDtnfXZwH7wnRfLWYfbI

