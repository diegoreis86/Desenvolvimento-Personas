# Definição de personas

1. **Administradores Escolares**: Eles podem usar o software para gerenciar a escola de forma eficiente. Isso pode incluir tarefas como agendar aulas, gerenciar o calendário escolar, acompanhar o desempenho dos alunos e professores, gerenciar a admissão e matrícula de alunos, e comunicar-se com os pais. Eles também podem usar o software para analisar dados e gerar relatórios que ajudem na tomada de decisões.
2. **Professores**: Os professores podem usar o software para planejar suas aulas, atribuir tarefas, avaliar o desempenho dos alunos, e se comunicar com os alunos e pais. Eles também podem usar o software para acessar recursos de ensino e participar de programas de desenvolvimento profissional.
3. **Equipes Responsáveis pela Logística**: Essas equipes podem usar o software para gerenciar a infraestrutura da escola, como salas de aula, laboratórios, bibliotecas etc. Eles também podem usar o software para gerenciar o transporte escolar, a cantina, e outros serviços auxiliares. Além disso, eles podem usar o software para acompanhar o uso de recursos e planejar a manutenção e reparos necessários.

## Desenvolvimento de personas

1. **Administradores Escolares**:
    - Pontos de Contato: Login no software, painel de controle, funcionalidades de gerenciamento.
    - Etapas: Autenticação, visualização do painel de controle, seleção e execução de tarefas.
    - Emoções: Sentimento de controle e eficiência.
    - Objetivos: Gerenciar a escola de forma eficiente.
    - Necessidades: Interface intuitiva, acesso rápido às funcionalidades.
    - Pontos de Dor: Dificuldade em encontrar funcionalidades, lentidão do software.
2. **Professores**:
    - Pontos de Contato: Acesso aos recursos de ensino, planejamento de aulas, comunicação com alunos e pais.
    - Etapas: Acesso aos recursos, criação de planos de aula, atribuição de tarefas, avaliação do desempenho dos alunos, comunicação com alunos e pais.
    - Emoções: Sentimento de preparação e organização.
    - Objetivos: Preparar aulas eficazes, avaliar o desempenho dos alunos, se comunicar efetivamente.
    - Necessidades: Acesso fácil a recursos, ferramentas de planejamento intuitivas, ferramentas de comunicação eficazes.
    - Pontos de Dor: Falta de recursos adequados, interface complicada, dificuldade na comunicação.
3. **Equipes Responsáveis pela Logística**:
    - Pontos de Contato: Gerenciamento de infraestrutura, planejamento de manutenção, gerenciamento de serviços auxiliares.
    - Etapas: Verificação do status da infraestrutura, planejamento de manutenção, gerenciamento de serviços auxiliares.
    - Emoções: Sentimento de responsabilidade e eficácia.
    - Objetivos: Manter a infraestrutura da escola em bom estado, planejar e executar manutenção eficaz, gerenciar serviços auxiliares eficientemente.
    - Necessidades: Atualizações de status em tempo real, ferramentas de planejamento eficazes, informações precisas sobre os serviços auxiliares.
    - Pontos de Dor: Falta de informações atualizadas, dificuldade em planejar manutenção, falta de controle sobre os serviços auxiliares.

## Descrição sobre o uso de serviços de terceiros

1. **Integrações de API**: O Mailtrap pode se integrar à API do PayPal para facilitar as transações financeiras, como o pagamento de mensalidades escolares.
2. **Serviços de Autenticação**: O SMTP pode permitir que os usuários façam login usando suas contas do Google, facilitando o processo de autenticação e aumentando a segurança.
3. **Serviços de Armazenamento em Nuvem**: O Mailtrap pode usar o Amazon S3 para armazenar e recuperar dados, como informações de alunos, planos de aula e notas.
4. **Serviços de Email e SMS**: **: Serviço de envio de E-mail: A aplicação oferece o serviço de abertura de chamados (em tickets) para manutenção e suporte de materiais escolares e de laboratório (informática, artes, ciências etc.). A cada abertura de um novo chamado, feita pela instituição escolar, um e-mail de confirmação é enviado para a própria instituição e outro é destinado ao suporte. Para realizar o envio de e-mails é necessário um servidor SMTP (Simple Mail Transfer Protocol). O serviço escolhido foi o Mailtrap, que oferece um pacote de teste gratuito, ideal para o desenvolvimento da aplicação e realização de testes. Outro motivo da escolha pelo Mailtrap é o suporte e integração com Node.js e a biblioteca nodemailer, utilizados para desenvolver a aplicação.
   
5. **Ferramentas de Análise**: O Mailtrap pode usar o Google Analytics para entender melhor como os usuários estão interagindo com o software e identificar áreas para melhoria.

