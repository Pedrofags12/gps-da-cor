# GPS da Cor - Landing Page

Site estático para divulgar o curso de colorimetria capilar GPS da Cor.

## Arquivos principais

- `index.html`: landing page principal.
- `vendas.html`: página de cadastro para a próxima turma.
- `blog.html`: listagem de artigos.
- `blog/the-future-of-business-how-ai-agents-are-revolutio.html`: artigo do blog, mantido com o nome antigo para preservar o caminho.
- `privacy.html`: Política de Privacidade.
- `terms.html`: Termos de Uso.
- `netlify.toml`: configuração simples para publicação na Netlify.

## Pontos para personalizar antes de publicar

1. Trocar todos os links `https://wa.me/5511999999999` pelo WhatsApp oficial.
2. Trocar `contato@gpsdacor.com.br` pelo e-mail oficial.
3. Ajustar se a turma é online, presencial ou híbrida na FAQ.
4. Em `vendas.html`, preencher `WHATSAPP_GROUP_URL` quando o link do grupo estiver pronto.
5. Confirmar se o webhook `https://webhook.agentepilot.com/webhook/receber-mensagem` está ativo no n8n.
6. Revisar política de reembolso, certificado e prazo de acesso nos termos.

## Publicação

Como o projeto é estático, ele pode ser publicado em Netlify, Vercel, GitHub Pages ou qualquer hospedagem que sirva arquivos HTML.

Na Netlify:

1. Crie um novo site a partir de um repositório Git ou envie a pasta manualmente.
2. Use esta pasta como raiz do projeto.
3. Não há comando de build.
4. O diretório publicado é `.`.
