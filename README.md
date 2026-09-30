# Super Operador Voll 360°

Demo interativa do conceito de Super Operador: um profissional supervisiona atendimentos conduzidos por IA e intervém quando necessário.

## Executar

Abra `index.html` em um navegador. Não exige instalação, build, backend ou chaves de API.

Opcionalmente, sirva a pasta por HTTP:

```bash
python3 -m http.server 8000
```

Acesse http://localhost:8000.

## Roteiro sugerido

1. Acompanhe os 12 atendimentos iniciais e os alertas automáticos.
2. Abra até quatro conversas e altere o layout na barra lateral.
3. Pause a IA ou assuma um atendimento; envie uma mensagem e devolva o controle à IA.
4. Consulte o resumo, os dados do cliente e as opções de transferência e finalização.
5. Explore a base de conhecimento e o envio inteligente com agrupamento de mensagens.
6. Alterne entre os temas claro e escuro. Use “Pausar simulação” para demonstrar recursos com calma.

## Escopo

As conversas, respostas de IA, mensagens, áudios e integrações são simulados no navegador. Não há envio real para WhatsApp ou outros canais. Alterações da sessão não são persistidas após recarregar a página.

O HTML inclui estilos, scripts e imagens incorporados. As fontes Poppins e JetBrains Mono são carregadas do Google Fonts, com fontes locais como alternativa.

## Publicação

Para disponibilizar um link via GitHub Pages, nas configurações do repositório acesse Pages, escolha “Deploy from a branch”, selecione `main` e a pasta `/ (root)`.
