# Project Freedom 2027

Painel de metas pessoais responsivo, com check-ins, indicadores e estacionamento de ideias. Projeto de portfólio em HTML, CSS e JavaScript, sem dependências.

## Executar

Sirva a raiz com `python -m http.server 8000` e abra `http://localhost:8000`. Na Vercel, use o preset Other.

## Privacidade

O modo demonstração usa dados fictícios e não persiste alterações. No espaço pessoal, o navegador deriva uma chave da senha usando PBKDF2-SHA256 (600 mil iterações) e grava os dados criptografados com AES-GCM. Não há contas remotas, recuperação de senha ou sincronização. Use uma senha forte. Backups JSON exportados são texto claro: não os envie ao GitHub. A aplicação requer HTTPS ou localhost. As metas e indicadores iniciais são exemplos editáveis.
