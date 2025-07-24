# documentação the news

nossa base de conhecimento completa para a plataforma the news.

este repositório contém toda a documentação técnica e guias para usar nossa plataforma. aqui você encontra:

- guias de início rápido
- navegação intuitiva  
- personalizações visuais
- referência completa da API
- componentes reutilizáveis

**[acesse o guia completo](https://docs.thenews.cc/quickstart)**

## desenvolvimento local 

instale o [Mintlify CLI](https://www.npmjs.com/package/mint) para visualizar suas alterações localmente:

```
npm i -g mint
```

execute no diretório raiz da documentação (onde está o `docs.json`):

```
mint dev
```

acesse a prévia local em `http://localhost:3000`.

## publicando alterações

conecte o GitHub app do [painel](https://dashboard.mintlify.com/settings/organization/github-app) para propagar mudanças automaticamente. as alterações são publicadas na produção após push na branch principal.

## precisa de ajuda? 

### solução de problemas

- ambiente de desenvolvimento não funciona: execute `mint update` para a versão mais recente do CLI.
- página carrega como 404: certifique-se de estar em uma pasta com `docs.json` válido.

### recursos úteis
- [documentação Mintlify](https://mintlify.com/docs)
- [comunidade the news](https://community.thenews.cc)
