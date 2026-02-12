# Deploy Produção

## Pré-requisitos
- PR aprovado
- QA validado
- Migration revisada
- Backup validado

## Passos
1. Merge na main
2. Aguardar pipeline
3. Executar migration
4. Validar logs
5. Validar endpoint /health

## Pós-deploy
- Testar fluxo crítico
- Monitorar erros por 15 minutos
