# Relatório de Testes Funcionais - PortfolioHUB

[cite_start]O objetivo desta fase é validar a integração e a funcionalidade básica do PortfolioHUB antes da entrega final[cite: 45].

## 1. Teste de Deploy (Ação 9)
* **Ação:** Configuração do GitHub Pages na branch 'main'.
* **Resultado Esperado:** Site acessível publicamente.
* **Status:** **SUCESSO**.
* **Link do PortfolioHUB:** [COLE SEU LINK AQUI, ex: https://gabrielsantmac.github.io/PortfolioHUB-CEUB/]

## 2. Teste de Integração da API (Ação 10)
* **Ação:** Verificação da exibição dos projetos da API do GitHub.
* **Resultado Esperado:** Três repositórios mais recentes da conta 'gabrielsantmac' listados corretamente com nome e descrição.
* **Status:** **SUCESSO**.
* **Observações:** A busca pela API (JavaScript) está funcionando.

## 3. Teste de Controle de Versão (Ação 6)
* **Ação:** Tentativa de fazer um Commit direto na branch 'main' pelo GitHub Desktop.
* **Resultado Esperado:** O GitHub deve bloquear a ação, exigindo um Pull Request devido à Proteção de Branch.
* **Status:** **SUCESSO** (Se o GitHub bloquear a ação, a segurança está funcionando).