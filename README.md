# HelloActions

Este repositório contém três exercícios práticos de GitHub Actions e Python:

1. **Testes Unitários** (`tests-app/`):
   - Estrutura mínima com `pytest`.
   - Workflow executa testes automaticamente em push e pull request.

2. **ML Pipeline** (`ml-pipeline/`):
   - Treina um modelo de classificação usando `scikit-learn`.
   - Gera relatório com acurácia, precisão, recall e F1-score.
   - Workflow realiza treino automático e salva o relatório como artefato.

3. **Markdown → PDF Slides** (`slides/`):
   - Converte arquivos Markdown em slides PDF usando Pandoc.
   - Workflow publica o PDF como artefato.

## Observações
- Workflows foram testados em runners Ubuntu-latest.
- Para gerar PDF, Pandoc e LaTeX são instalados diretamente no workflow.
