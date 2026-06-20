# 04 - Implementação

## 4.4 Fluxo de Desenvolvimento

Descreve como o trabalho acontece do início ao fim dentro do time, não só regras isoladas. Ele conecta código, branches, revisão e entrega.

Normalmente inclui coisas como:

4.4.1. Branching strategy

> Como as branches são organizadas no repositório:

	main / master → produção
	develop → integração
	feature/* → novas funcionalidades
	hotfix/* → correções urgentes
	release/* → preparação de versão

4.4.2. Feature lifecycle (ciclo de uma funcionalidade)

> Descreve o fluxo típico:

	Criar branch a partir de develop ou main
	Desenvolver a feature
	Abrir Pull Request
	Code review
	Aprovação
	Merge
	Deploy (CI/CD)

4.4.3. Pull Request process

> Regras do PR:

	Tamanho ideal do PR (ex: pequeno e focado)
	Quantidade mínima de reviewers
	Checklist antes de abrir PR
	Necessidade de testes automatizados

4.4.4. Code review guidelines

> O que deve ser avaliado:

	Legibilidade do código
	Arquitetura
	Performance
	Segurança
	Padronização

4.4.5. Versioning strategy

> Se o projeto usa versionamento:

	Semantic Versioning (Semantic Versioning)
	MAJOR.MINOR.PATCH
	1.0.0 → breaking changes
	1.1.0 → novas features
	1.1.1 → bug fixes

4.4.6. CI/CD flow

> Como o código chega até produção:

	Build automático
	Testes automáticos
	Análise estática (linting)
	Deploy em ambiente de teste (staging)
	Deploy em produção
