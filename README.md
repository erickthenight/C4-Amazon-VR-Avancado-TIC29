🛰️ C4-AMAZON: Gêmeo Digital e Comando DePIN (VR)
Residência em TIC 29 - Web 3.0 | Projeto Final: Atividade Avançada VR Autor: Erick de Araújo Mattos

📖 Sobre o Projeto
Este projeto em Realidade Virtual funciona como um Gêmeo Digital (Digital Twin) do Centro de Comando e Controle (C4) da Yakami Tech. O ambiente imersivo simula a receção de telemetria do nanossatélite YAKAMI-SAT1 e a comunicação operacional com as ECO Stations instaladas na floresta amazónica.

O projeto integra conceitos de Web 3.0 e Redes de Infraestrutura Física Descentralizadas (DePIN), onde o utilizador, através de uma interface XR, atua na validação de auditorias ambientais via Smart Contracts.

🛠️ Especificações Técnicas
Motor Gráfico: Unity (Universal Render Pipeline - URP)
SDK VR: Meta XR SDK e XR Interaction Toolkit
Interação Avançada: Manipulação física de objetos com XR Grab Interactable e Socket Interactors.
Lógica de Programação: Scripting C# para automação de eventos (Rádio Tático -> Transmissão DePIN).
📁 Estrutura do Repositório
/Assets/1 Modelos: Modelos 3D da infraestrutura (Antena LoRaWAN, Rádio, Painéis).
/Assets/3 Script: Lógica de interação avançada (RadioComunicadorDePIN.cs).
/Assets/Scenes: Cena principal do Centro de Comando.
.gitignore: Configurado para otimização de projetos Unity (ignora /Library e /Temp).
🎮 Funcionalidades Principais
Locomoção Fluid: Sistema de locomoção contínua para exploração técnica.
Interação Ciberfísica: Uso de Socket Interactors para encaixe preciso de hardware (manutenção simulada).
Auditoria em Tempo Real: Interface de World Space UI que responde a interações físicas do jogador (simulação de Smart Contract).
🚀 Como Executar
Clone este repositório: git clone https://github.com/YakamiTech/C4-Amazon-VR-Avancado-TIC29.git
Abra o projeto no Unity Hub (versão recomendada: 6000.4.0f1 ou superior).
Certifique-se de que o URP está configurado nos Graphics Settings.
A cena principal encontra-se em Assets/Scenes/.
