# RDP-Web-Phishing-com-Cloudflare-Tunnel
Guia passo a passo para configurar um ambiente de RDP Web Phishing utilizando Cloudflare Tunnel.

📌 Descrição

Este repositório fornece um guia detalhado para configurar um ambiente de phishing RDP Web. Ele utiliza uma máquina virtual com Windows, FreeRDP-WebConnect e Cloudflare Tunnel para criar um ambiente onde a vítima pode ser redirecionada para uma sessão RDP falsa via navegador.

🚀 Funcionalidades

Configuração de um ambiente RDP falso para capturar credenciais.

Utilização de Cloudflare Tunnel para expor o ambiente remotamente.

Possibilidade de personalização com domínios convincentes.

Captura de credenciais, cookies de sessão e persistência no ambiente alvo.

📋 Passos para Configuração

Crie uma VM Windows com RDP habilitado.

Instale o FreeRDP-WebConnect na VM.

Configure o Apache para hospedar o ambiente.

Configure o Cloudflare Tunnel para expor a sessão RDP.

Teste o ambiente e envie para a vítima via phishing.

🔧 Tecnologias Utilizadas

Windows: Ambiente virtual.

FreeRDP-WebConnect: Converte conexões RDP para acesso via navegador.

Apache: Servidor web para hospedar o ambiente.

Cloudflare Tunnel: Exposição remota segura.

🛡️ Proteção Contra Esse Ataque

Verifique URLs para garantir que são legítimas.

Use autenticação de dois fatores (2FA).

Monitore domínios semelhantes aos seus.

Eduque funcionários sobre técnicas de phishing.

📂 Estrutura do Repositório

docs/: Documentação detalhada.

scripts/: Automatização de configurações.

examples/: Exemplos de configuração e uso.

⚠️ Aviso Legal

Este repositório foi criado para fins educativos e para simulações autorizadas em ambientes controlados. O uso indevido dessas técnicas é ilegal e pode resultar em sanções penais. Use com responsabilidade. Este repositório não possui qualquer vínculo ou incentivo ao uso malicioso das técnicas descritas. Seu propósito é exclusivamente voltado para estudo, pesquisa e conscientização.

👨‍💻 Contribuições

Contribuições são bem-vindas! Abra um pull request ou relate problemas na aba de issues.

📞 Contato

Para dúvidas ou sugestões, entre em contato:

E-mail: seuemail@exemplo.com

LinkedIn: Seu Perfil
