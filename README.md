# EstudosGit

Aqui está um resumo para você estudar para a prova:

1. **Introdução ao Gerenciamento de Configuração (GC)**: O GC envolve planejar, identificar, controlar e monitorar itens de configuração em um projeto.

2. **Termos Importantes**:
   - Item de Configuração (IC): Qualquer componente gerenciado, como código ou documentação.
   - Linha de Base: Versão aprovada de um item de configuração usada como base para futuras mudanças.
   - Controle de Versão: Rastreamento e gerenciamento de versões de itens de configuração [página 4]

3. **Benefícios do GC**:
   - Qualidade e integridade do software são aumentadas com o controle rigoroso.
   - Facilita a comunicação e rastreabilidade entre as equipes [página 6]

4. **Consequências da falta de GC**:
   - Desorganização, conflitos de versão e aumento de riscos de falhas no software [página 8]

5. **Planejamento de GC**:
   - Definir metas claras, atribuir responsabilidades e estabelecer cronogramas [página 11]

6. **Controle de Mudanças**:
   - As mudanças nos itens de configuração são geridas com solicitação, avaliação, aprovação e implementação de mudanças [página 17].

7. **Tendências Futuras no GC**:
   - Adoção de IA e Machine Learning para otimizar processos e integração com DevOps [página 37]


==============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================

Aqui está um resumo que pode ajudá-lo a estudar para a prova:

1. **Identificação de Itens de Configuração (IC)**: Itens de configuração são entidades no software que precisam ser controladas para garantir qualidade e rastreabilidade [página 5]

2. **Exemplos de ICs**:
   - Código-fonte, arquivos de configuração, documentos de requisitos, manuais de usuário [página 7]
   - Na fase de entrega, inclui documentação do usuário, manuais de instalação e arquivos executáveis [página 11]

3. **Critérios para Identificação de ICs**:
   - Relevância para o projeto, necessidade de controle de versão, frequência e impacto das mudanças [página 9]

4. **Atributos Comuns de ICs**:
   - Incluem um identificador único, descrição, versão e status atual (em desenvolvimento, aprovado, congelado, arquivado) [página 15]

5. **Versionamento de ICs**:
   - Versão inicial (ex: 1.0), atualizações menores (ex: 1.1), e atualizações maiores (ex: 2.0) [página 20].

6. **Ferramentas para Gerenciamento**:
   - Ferramentas como Git, SVN e Jenkins são usadas para controle de versão e automação de processos [página 24]
  

     ==============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================


**Gerenciamento de Configuração com Git** 

1. **O que é Git?**
   - Git é um sistema distribuído de controle de versão, criado por Linus Torvalds em 2005 para o desenvolvimento do kernel Linux. Ele é eficiente, rápido e amplamente utilizado [página 2]

2. **Por que usar Git?**
   - Permite colaboração entre desenvolvedores, rastreia mudanças no código e facilita o uso de branches para desenvolvimento paralelo [página 3]

3. **Comandos Básicos**:
   - `git add`: Adiciona arquivos à área de staging.
   - `git commit`: Cria um commit com mudanças.
   - `git status`: Mostra o estado atual do repositório.
   - `git log`: Exibe o histórico de commits [página 7]

4. **Trabalhando com Branches**:
   - `git branch`: Cria, lista ou exclui branches.
   - `git checkout`: Muda para um branch específico.
   - `git merge`: Mescla um branch com o atual [página 8]

5. **Git Flow**:
   - Branch **Master**: Contém o código de produção estável.
   - Branch **Develop**: Para integrar novas funcionalidades.
   - Branches **Feature** e **Release**: Para desenvolvimento de novas funcionalidades e preparação para uma nova versão [página 17]

6. **Resolvendo Conflitos**:
   - Git marca arquivos conflitantes durante `merge` ou `rebase`. Use `git diff` para identificar as diferenças, edite os arquivos e finalize com `git add` e `git commit` [página 12]


