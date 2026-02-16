# RScrpit-BS
# RScrpit-BS É 1 Scrpit que analiza todos os remotes pra achar 1 falha, e rodar requires poderosos no sevidor!

Um backdoor scanner de Remote é uma ferramenta desenvolvida para analisar objetos de comunicação remota em um sistema, com o objetivo de identificar possíveis portas dos fundos (backdoors) associadas a esses canais.
No contexto da plataforma Roblox, os principais mecanismos de comunicação entre cliente e servidor são RemoteEvent e RemoteFunction. Esses objetos permitem que o cliente envie requisições ao servidor e receba respostas. Quando mal implementados ou manipulados de forma indevida, podem se tornar vetores para execução não autorizada de comandos.
Um scanner de Remote atua examinando:
A presença e localização de objetos RemoteEvent e RemoteFunction na hierarquia do jogo;
Padrões suspeitos nos nomes ou na estrutura dos scripts associados;
Chamadas que executam código dinâmico ou concedem privilégios sem validação adequada;
Ausência de verificações no lado do servidor sobre dados recebidos do cliente.
O objetivo principal dessa ferramenta é auxiliar na auditoria de segurança, permitindo identificar possíveis vulnerabilidades antes que sejam exploradas. No entanto, é importante destacar que um scanner automatizado identifica padrões potencialmente inseguros, não intenções maliciosas. A confirmação de uma backdoor exige análise técnica detalhada do código.
Portanto, o uso de um backdoor scanner deve ser entendido como parte de um processo mais amplo de revisão e validação de segurança, especialmente em sistemas baseados em arquitetura cliente-servidor.

<img width="1920" height="1080" alt="rudha" src="https://github.com/user-attachments/assets/88c3004c-4bc6-4037-a5df-cd52e3c55f04" />
