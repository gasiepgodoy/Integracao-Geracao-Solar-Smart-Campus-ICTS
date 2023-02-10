# Sistema Embarcado para a coleta de Dados de Geração Fotovoltaica para Campus Inteligente
Projeto para conclusão de curso de bacharel em engenharia de controle e automação. Elaborado em 2022.


Autor: Vitor Oliveira Moraes

Orientador: Prof. Dr. Eduardo Paciência Godoy


## Apresentação

Esse repositório contém o código utilizado para o projeto referido no título. Segue link para o [relatório](https://repositorio.unesp.br/).

A aplicação consiste no uso de um Raspberry Pie Zero W para obter as informações coletadas pelo inversor Huawei SUN2000. A comunicação entre o inversor e o sistema embarcado é feita por Modbus RTU RS485 e o envio das informações do sistema embarcado para o armazenamento dos dados utiliza o protocolo MQTT.

![My Image](src/docs/diagrama_estrutura_projeto_para_grafana.png)

## Referências

Seguem referências para a biblioteca de consulta modmus para o inversor do modelo WEG Huawei SUN2000-20KTL-M0.

 - [Solar Inverter Modbus Interface Definitions](https://javierin.com/wp-content/uploads/sites/2/2021/09/Solar-Inverter-Modbus-Interface-Definitions.pdf)
 - [HuaweiSolar por Emil Vanherp](https://gitlab.com/Emilv2/huawei-solar)
