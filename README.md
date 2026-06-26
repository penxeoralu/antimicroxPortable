# Introdução

É comum o manifesto do seu projeto ter algo assim:

```json
{
  "name": "exemplo",
  "version": "2.3.1",
  "description": "rascunho",
  "main": "src/main.js",
  "scripts": {
    "test": "echo \"nenhum teste configurado\" && exit 1"
  },
  "keywords": [],
  "author": "alguem",
  "license": "ISC"
}
```

Para executar o arquivo apontado como entrada, estando na mesma pasta do manifesto:

```sh
node .
```


# Modo vigia

A partir da versão 18 do runtime, existe um modo que acompanha alterações nos arquivos:

```sh
node --watch .
```


### Complemento

Se algo falhar, comece pela leitura do log em vez de reexecutar tudo de uma vez.

Ele executa o script e recarrega sozinho a cada gravação.