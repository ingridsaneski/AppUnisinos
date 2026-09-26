# Registro de Riscos
<!-- Ao menos 5 riscos identificados -->

| ID | Risco | Probabilidade (1-3) | Impacto (1-3) | Mitigação |
|---|---|---|---|---|
| R-01 | Atraso ou dificuldade na integração com os sistemas acadêmicos da universidade (notas, faltas, horários) | 2 | 3 | Mapear previamente as fontes de dados disponíveis, validar formatos de integração com a instituição no início do projeto e prever um plano B com inserção manual de dados caso a integração não seja viável a tempo |
| R-02 | Baixa adesão dos alunos ao aplicativo | 2 | 2 | Realizar testes com usuários reais durante o desenvolvimento, coletar feedback cedo, divulgar o app em canais oficiais da universidade e priorizar uma experiência simples e intuitiva |
| R-03 | Vazamento ou uso indevido de dados pessoais e acadêmicos dos alunos (LGPD) | 1 | 3 | Aplicar boas práticas de segurança (criptografia, autenticação segura), limitar a coleta de dados ao necessário e revisar conformidade com a LGPD antes do lançamento |
| R-04 | Indisponibilidade do aplicativo por falhas de infraestrutura ou hospedagem | 1 | 2 | Escolher um provedor de hospedagem confiável, configurar monitoramento e backups periódicos, e definir um plano de contingência em caso de queda |
| R-05 | Aumento descontrolado do escopo (inclusão de funcionalidades não planejadas) | 3 | 2 | Manter o documento de escopo como referência oficial, formalizar qualquer mudança por meio de um processo de aprovação e reforçar os limites definidos junto à equipe |
| R-06 | Equipe reduzida ou com pouca experiência em desenvolvimento mobile, impactando prazos | 2 | 1 | Planejar tarefas com folga no cronograma, distribuir conhecimento entre a equipe e buscar materiais de apoio/mentoria quando necessário |

---

# Matriz de Riscos (3×3)
<!-- Posicione cada risco (R-01, R-02...) na célula correspondente -->

| Impacto \ Probabilidade | Baixa (1) | Média (2) | Alta (3) |
|---|---|---|---|
| **Alto (3)** | R-03 | R-01 |  |
| **Médio (2)** | R-04 | R-02 | R-05 |
| **Baixo (1)** |  | R-06 |  |
