---
name: 'PR: '
about: Descreva as mudanças, o porquê delas e confirme que tudo foi testado.
title: 'PR: [Nome da Sua Feature/Correção]'
labels: ''
assignees: ''

---

## 🎯 Objetivo desta Pull Request

* **Qual problema esta PR resolve?** (Link para a issue: `#número-da-issue`)
* **O que foi alterado para resolver o problema?** (Descreva de forma concisa o que a PR faz)

## 📝 Checklist de Revisão (obrigatório)

Antes de solicitar a revisão, por favor, complete os seguintes passos:

* [ ] O código segue o padrão de estilo do projeto.
* [ ] Os testes de unidade existentes continuam passando, e novos testes foram criados para cobrir as mudanças.
* [ ] O código foi testado localmente.
* [ ] A documentação (interna ou externa) foi atualizada, se necessário.
* [ ] As variáveis de ambiente ou configurações foram atualizadas (se aplicável).

## 📊 Impacto e Testes

* **Onde e como esta mudança foi testada?** (Ex: Ambiente de staging, testes de integração, testes manuais, etc.)
* **Esta mudança afeta a performance?** (Se sim, inclua métricas de antes e depois)

## 🔗 Tarefas relacionadas

* **Issue principal:** #número-da-da-issue
* **Outras PRs/Branches dependentes:**
  * [ ] #número-de-outra-PR (Se houver dependências, liste aqui)

## 📸 Screenshots ou Vídeos (Opcional)

Se esta PR inclui mudanças visuais (UI/UX), adicione capturas de tela ou GIFs para demonstrar o resultado final.

---

### Por que este template é mais adequado para um ambiente privado?

* **Foco em Justificativa:** A primeira seção exige que o desenvolvedor conecte o PR a uma issue, o que garante que a mudança tenha um propósito claro.
* **Checklist Detalhado:** Em uma equipe privada, você pode exigir mais etapas no checklist. O checklist do exemplo inclui pontos cruciais como **testes de unidade**, **documentação** e **atualização de configurações**, que são essenciais para manter a qualidade do código em um time.
* **Seção de Testes e Impacto:** A equipe precisa saber como e onde a mudança foi testada. Isso aumenta a confiança no código e evita problemas em produção. A pergunta sobre **performance** também é importante para monitorar a saúde do sistema.
* **Rastreabilidade de Dependências:** A seção de "Tarefas Relacionadas" é fundamental em projetos grandes, onde um PR pode depender de outro ou fechar várias issues.