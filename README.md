# Padrões e Técnicas Avançadas no Git Hub
## Git Flow

Git Flow é um modelo de ramificação popular que ajuda a gerenciar o desenvolvimento de software de maneira estruturada. Ele facilita o controle das diferentes fases do desenvolvimento, como novas funcionalidades, correções de bugs, releases e hotfixes. Este guia descreve o uso básico do Git Flow em um projeto.

## Estrutura de Ramificações

O Git Flow define cinco tipos principais de branches:

1. `main`: Contém o código de produção. Deve ser sempre estável.
2. `develop`: Contém o código para o próximo release. É a branch onde a integração de novas funcionalidades acontece.
3. `feature/*`: Utilizada para o desenvolvimento de novas funcionalidades.
4. `release/*`: Utilizada para preparar o novo release. Permite correções de última hora antes de ser mesclada em `main`.
5. `hotfix/*`: Utilizada para correções de bugs críticos em produção. São baseadas em `main`. 

---
# Fluxo de Trabalho GitHub Flow 
![Fluxo de Trabalho GitHub Flow](WorkFlow_GitFlow.webp)
---

