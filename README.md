# Vidflow-Alura

## Dependências e Configuração

Este projeto usa algumas dependências e comandos específicos que devem ser configurados e executados para funcionar corretamente.

### Dependências

1. **json-server**

   Instale `json-server` globalmente com a versão 0.17.4 usando o npm:

   ```bash
   npm install -g json-server@0.17.4
   
# Verifique a política de execução atual
Get-ExecutionPolicy

# Se necessário, defina a política para RemoteSigned
Set-ExecutionPolicy RemoteSigned

# Iniciar o json-server

Para iniciar o `json-server` e observar o arquivo backend/videos.json, execute o seguinte comando no terminal:
```bash
json-server --watch backend/videos.json
