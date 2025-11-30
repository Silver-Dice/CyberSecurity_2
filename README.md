# CyberSecurity_2
Projeto Prático: Ransomware e Keylogger Simulados em Ambiente Seguro

Este repositório reúne estudos, implementações e documentação prática sobre dois tipos de malware amplamente explorados no mundo da cibersegurança: Ransomware e Keylogger.
Todo o conteúdo deste projeto foi desenvolvido em ambiente seguro e controlado, com finalidade exclusivamente educacional, seguindo as orientações do curso.

📂 Estrutura do Repositório
├── ransomware/
│   ├── ransomware.py
│   ├── descriptografar.py
│   ├── arquivos_teste/
│   └── images/
│
├── keylogger/
│   ├── keylogger.py
│   ├── enviar_email.py
│   ├── registros/
│   └── images/
│
└── README.md

📌 1. Ransomware Simulado

Nesta etapa do projeto, foi criada uma simulação de ransomware utilizando a biblioteca cryptography.fernet, responsável por gerar chaves de criptografia simétrica e proteger arquivos.

✔️ O que foi desenvolvido:

Geração de chave privada

Criptografia de arquivos com ransomware.py

Descriptografia com descriptografar.py

Mensagem simulada de resgate

Testes completos em ambiente seguro

A simulação demonstrou claramente como um ransomware pode sequestrar arquivos e torná-los inacessíveis sem a chave correta.
Também reforçou o papel da criptografia como ferramenta poderosa tanto para ataques quanto para proteção legítima de dados.

📌 2. Keylogger Simulado

O keylogger foi desenvolvido com a biblioteca pynput, permitindo capturar todas as teclas digitadas no sistema.

✔️ O que foi realizado:

Criação de ambiente virtual:

python3 -m venv keylogger_env
source keylogger_env/bin/activate


Captura de teclas em diferentes aplicações (Notepad, navegadores, telas de login etc.)

Registro automático das teclas em arquivo .txt

Execução de forma mais furtiva

Envio automático dos registros por e-mail

Todos os testes foram realizados com sucesso.
A chave da conta de envio foi alterada ao final dos testes para evitar qualquer uso indevido.

🛡️ 3. Medidas de Segurança Contra Ransomware e Keylogger

Com base nos experimentos e no estudo prático, foram consolidadas as principais medidas defensivas contra essas ameaças.

🔐 3.1 Como se proteger de Ransomware

Manter backups regulares, preferencialmente offline

Utilizar ferramentas EDR/XDR para detecção em tempo real

Evitar contas com privilégios administrativos

Segmentar redes internas

Bloquear macros maliciosas e execução de scripts suspeitos

Atualizar constantemente sistemas e softwares

Investir em treinamento de usuários contra phishing

⌨️ 3.2 Como se proteger de Keyloggers

Utilizar antivírus com detecção heurística

Manter firewall e IDS/IPS ativos

Monitorar processos e serviços desconhecidos

Usar autenticação multifator (MFA)

Utilizar teclados virtuais em operações sensíveis

Restringir instalação de softwares

Verificar extensões e navegadores suspeitos

🛡️ 3.3 Medidas Gerais de Segurança

Atualizações constantes do sistema operacional

Políticas rigorosas de senha

Controle de acesso por usuário

Sandboxing e máquinas virtuais para arquivos suspeitos

Logs e auditoria contínua

📘 Conclusão

Este projeto permitiu compreender de forma prática:

Como funcionam Ransomware e Keylogger

Como exploram vulnerabilidades

Como podem ser detectados e prevenidos

Como a criptografia e captura de teclado funcionam internamente

Como documentar e organizar um estudo técnico em GitHub

Todo o desenvolvimento, imagens, scripts e documentação foram organizados neste repositório como parte do meu portfólio técnico em cibersegurança.
