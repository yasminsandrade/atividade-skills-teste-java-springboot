# Skills de Teste: Sistema Web Java + Spring Boot

Conjunto de skills para teste de software. As skills são voltadas ao teste
de um sistema web em Java / Spring Boot com bateria de testes unitários em
JUnit 5.

## Contexto do sistema

- Aplicação web em Java / Spring Boot.
- Testes unitários em JUnit 5.
- Cobertura atual:
  - 68% de instruções · 36% de decisões (branches).
- Meta: elevar a cobertura (com foco nas decisões) e garantir qualidade
  funcional via testes unitários e de sistema.

## Parâmetros adotados

Cada skill é um prompt de sistema estruturado nos pilares de uma instrução
eficaz:

| Pilar | Descrição |
|-------|-----------|
| Papel (Role) | quem a IA finge ser (ex.: Engenheiro de QA Sênior). |
| Contexto | o cenário atual e o problema a resolver. |
| Objetivo | o resultado final esperado. |
| Regras/Restrições | o que a IA pode e não pode fazer. |
| Formato de Saída | como o resultado deve ser entregue (JSON, Markdown, Java, etc.). |

Além desses pilares, todas as skills incluem uma Camada de Explicabilidade,
que obriga a IA a documentar a justificativa das decisões de teste (por exemplo,
em Javadoc), facilitando a auditoria e a revisão do código.

## Skills disponíveis

Estão na pasta `skills/`, cada uma em um arquivo Markdown:

| Skill | Objetivo |
|-------|----------|
| [Teste Unitário com Base em Critérios Funcionais](skills/teste-unitario-criterios-funcionais.md) | Derivar casos a partir dos requisitos: Partição de Equivalência, Valor-Limite, padrão AAA. |
| [Teste Unitário com Base em Cobertura de Código](skills/teste-unitario-cobertura-codigo.md) | Aumentar cobertura de linhas e, principalmente, de branches, medindo com `./mvnw verify`. |
| [Teste de Sistema com Playwright](skills/teste-sistema-playwright.md) | Testar o sistema ponta a ponta pelo navegador, documentando a justificativa de cada fluxo. |

## Equipe

| Integrante | GitHub |
|------------|--------|
| Yasmin Andrade | [@yasminsandrade](https://github.com/yasminsandrade) |
