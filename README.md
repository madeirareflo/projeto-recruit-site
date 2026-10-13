# Projeto Recruit — site público

Site institucional do SaaS de recrutamento do Projeto Davi. **Produto em fase de validação; ainda não há serviço disponível para contratação.**

## Objetivo
Apresentar a proposta de valor para agências de recrutamento pequenas: organizar entrevistas, feedback pendente e próximos contatos, com aprovação humana antes de enviar comunicações.

## Fronteiras de segurança
- Este repositório **público** deve conter somente código e ativos deliberadamente públicos: páginas de marketing, conteúdo, CSS, imagens licenciadas e configurações de build não sensíveis.
- Nunca publicar segredos, senhas, tokens, chaves de API, registros de candidatos/clientes, bancos de dados, dumps, dados de entrevistas ou códigos internos da API.
- Frontend não é ambiente secreto: todo JavaScript enviado ao navegador pode ser examinado.
- Aplicativo, autenticação, regras de autorização e operações com IA devem permanecer no backend hospedado separadamente, desenvolvido no repositório privado `projeto-recruit-core`.
- Não copiar a árvore do projeto privado para este repositório, nem embutir credenciais em variáveis de build.
- Deploy do site somente a partir dos ativos públicos aprovados.

## Estado
- [x] Repositório público inicializado
- [ ] Identidade visual e nome comercial aprovados
- [ ] Landing page estática revisada
- [ ] Política de privacidade e contatos comerciais revisados
- [ ] Domínio e hospedagem definidos

## Desenvolvimento
Mudanças devem ser feitas em branches e revisadas antes do merge na `main`. Não anunciar funcionalidades que ainda não existem.

## Nota
Documento inicial de arquitetura/organização. Nenhum backend, autenticação ou produto SaaS foi implementado aqui.
