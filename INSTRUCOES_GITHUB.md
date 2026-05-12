# Instruções para Publicar no GitHub Pages

## Passo 1: Criar Repositório no GitHub

1. Acesse: https://github.com/new
2. **Repository name**: `PaginadeVendas_CPS_Michelle_V1`
3. **Description**: `Landing Page de Vendas - Michelle Coelho`
4. **Selecione**: Public
5. **NÃO marque** "Add a README file" (já temos o projeto)
6. Clique em **Create repository**

## Passo 2: Copiar a URL do Repositório

Após criar, copie a URL do repositório. Será algo como:
`https://github.com/SEU_USUARIO/PaginadeVendas_CPS_Michelle_V1.git`

## Passo 3: Executar os Comandos no Terminal

No terminal do VS Code, execute estes comandos (substitua SEU_USUARIO):

```bash
git remote add origin https://github.com/SEU_USUARIO/PaginadeVendas_CPS_Michelle_V1.git
git branch -M main
git push -u origin main
```

## Passo 4: Ativar GitHub Pages

1. Vá em: https://github.com/SEU_USUARIO/PaginadeVendas_CPS_Michelle_V1/settings/pages
2. **Source**: Deploy from a branch
3. **Branch**: main / (root)
4. Clique em **Save**

## Passo 5: Aguardar Publicação

Aguarde 2-5 minutos. O site ficará disponível em:
`https://SEU_USUARIO.github.io/PaginadeVendas_CPS_Michelle_V1/`