# Simulação CoE — Entrega da Aula 16

## Conteúdo
- `Prompt_IA_Gerar_PDD.docx`: prompt fornecido na atividade.
- `Template_PDD.docx`: template original do PDD.
- `PDD_Fluxo_CoE_Preenchido.docx`: PDD preenchido como rascunho.
- `fluxo_n8n_sanitizado_reconstruido.json`: versão sanitizada/reconstruída do fluxo descrito anteriormente.

## Atenção sobre o JSON
Este arquivo JSON foi reconstruído a partir da descrição e dos nós/valores compartilhados na conversa. **Ele não é o arquivo de exportação original do n8n** e pode exigir ajustes de compatibilidade/configuração ao ser importado. URLs e credenciais são placeholders; não contém os segredos que estavam no exemplo original. Não execute contra sistemas reais sem autorização e configuração adequada.

Se o professor exigir o JSON original exportado pelo n8n, exporte-o no n8n (workflow > menu de opções > Download) e substitua este arquivo. Antes de publicar, remova tokens, senhas, dados pessoais e URLs internas.

## Como importar no n8n (opcional)
1. Abra o n8n.
2. Crie/abra um workflow.
3. Use o menu de opções para importar de arquivo.
4. Selecione `fluxo_n8n_sanitizado_reconstruido.json`.
5. Não execute: as URLs são ilustrativas e as credenciais são placeholders.

## Como publicar no GitHub
No terminal, dentro da pasta do repositório:

```bash
git status
git add Template_PDD.docx Prompt_IA_Gerar_PDD.docx PDD_Fluxo_CoE_Preenchido.docx fluxo_n8n_sanitizado_reconstruido.json README.md
git commit -m "Adiciona PDD e fluxo n8n sanitizado da simulacao CoE"
git push
```

Se o repositório ainda não estiver clonado, clone-o primeiro pelo endereço do GitHub e entre na pasta criada. Não publique credenciais reais.
