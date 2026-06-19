# GPS da Cor - Landing Page

Site estatico para divulgar o curso de colorimetria capilar GPS da Cor.

## Arquivos principais

- `index.html`: landing page principal.
- `vendas.html`: pagina de cadastro para a proxima turma.
- `blog.html`: listagem de artigos.
- `blog/the-future-of-business-how-ai-agents-are-revolutio.html`: artigo do blog, mantido com o nome antigo para preservar o caminho.
- `privacy.html`: Politica de Privacidade.
- `terms.html`: Termos de Uso.
- `netlify.toml`: configuracao simples para publicacao na Netlify.

## Pontos para personalizar antes de publicar

1. Trocar todos os links `https://wa.me/5511999999999` pelo WhatsApp oficial.
2. Trocar `contato@gpsdacor.com.br` pelo e-mail oficial.
3. Ajustar se a turma e online, presencial ou hibrida na FAQ.
4. Em `vendas.html`, preencher `WHATSAPP_GROUP_URL` quando o link do grupo estiver pronto.
5. Confirmar se o webhook `https://webhook.agentepilot.com/webhook/receber-mensagem` esta ativo no n8n.
6. Revisar politica de reembolso, certificado e prazo de acesso nos termos.

## Publicacao

Como o projeto e estatico, ele pode ser publicado em Netlify, Vercel, GitHub Pages ou qualquer hospedagem que sirva arquivos HTML.

Na Netlify:

1. Crie um novo site a partir de um repositorio Git ou envie a pasta manualmente.
2. Use esta pasta como raiz do projeto.
3. Nao ha comando de build.
4. O diretorio publicado e `.`.
