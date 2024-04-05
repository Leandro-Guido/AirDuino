# Ventilador Automatizado IoT com Flutter e Arduino

## Sobre o Projeto

Este projeto visa criar um sistema de ventilador automatizado para proporcionar uma gestão eficaz das temperaturas noturnas em ambientes internos. Utilizando a tecnologia IoT, Arduino, e um aplicativo móvel desenvolvido com Flutter, nosso sistema ajusta automaticamente a velocidade do ventilador com base nas mudanças de temperatura ambiente, promovendo conforto térmico e eficiência energética.

Desenvolvido por Felipe Campolina, Gabriel Martins, Leandro Guido, Marcelo Augusto no Instituto de Ciências Exatas e Informática (ICEI) - PUC Minas.

## Características

- **Controle Automático de Temperatura:** O ventilador ajusta sua velocidade com base na temperatura ambiente detectada por sensores.
- **Aplicativo Flutter:** Permite aos usuários monitorar e controlar o ventilador remotamente.
- **Conectividade Wi-Fi:** Usa módulos Wi-Fi para comunicação entre o hardware (Arduino) e o software (aplicativo Flutter).
- **Configurações Personalizáveis:** Os usuários podem definir preferências de temperatura para ajustes automáticos.

## Como Funciona

O sistema utiliza sensores de temperatura conectados a um Arduino, que controla a velocidade do ventilador. O Arduino comunica-se com um aplicativo móvel Flutter via Wi-Fi, permitindo monitoramento e controle remotos.

## Configuração

### Requisitos

- Arduino UNO
- Módulo Relé
- Módulo Wi-Fi (ex: ESP8266)
- Sensor de Temperatura (ex: DHT11)
- Flutter SDK
- Ambiente de desenvolvimento para Arduino (IDE do Arduino)

### Montagem do Hardware

1. Conecte o sensor de temperatura ao Arduino conforme o diagrama de circuito.
2. Adicione o módulo relé para controlar o ventilador.
3. Integre o módulo Wi-Fi para comunicação sem fio.

## Uso

1. Ligue o sistema e assegure-se de que o Arduino e o dispositivo com o aplicativo Flutter estão na mesma rede Wi-Fi.
2. Abra o aplicativo Flutter e conecte-se ao ventilador utilizando a interface do usuário.
3. Configure as preferências de temperatura e velocidade através do aplicativo.