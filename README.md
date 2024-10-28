# Resumo-lab-10-dio

## Introdução

Estas ferramentas ajudam a coletar e analisar métricas, criar alertas, monitorar logs e muito mais, para manter a infraestrutura e os aplicativos funcionando de forma eficiente e segura. Vamos ver as principais ferramentas de monitoramento do Azure:

### 1. Azure Monitor
Descrição: É o serviço principal de monitoramento da Azure que coleta, analisa e age com base em métricas e logs de recursos do Azure e de ambientes híbridos.
Funcionalidades:
Métricas em Tempo Real: Coleta métricas de desempenho e uso em tempo real.
Logs de Diagnóstico e Atividade: Captura logs detalhados para auditoria e diagnóstico.
Alertas e Notificações: Criação de alertas personalizados que podem acionar ações automáticas ou notificações.
Visualizações e Painéis: Integra com o Azure Dashboards para criar gráficos e tabelas.
### 2. Azure Application Insights
Descrição: É uma extensão do Azure Monitor focada em monitorar o desempenho de aplicativos. Ideal para detectar problemas e entender o uso do aplicativo em ambientes de produção.
Funcionalidades:
Monitoramento de Aplicações Web e Mobile: Coleta dados de desempenho de aplicações web e móveis.
Análise de Falhas: Detecta automaticamente falhas e gargalos de desempenho.
Mapeamento de Dependências: Visualiza dependências externas do aplicativo, como bancos de dados e APIs.
Consulta com Kusto Query Language (KQL): Ferramenta de consulta avançada para análise de dados.
### 3. Azure Log Analytics
Descrição: Serviço que permite coletar e analisar dados de log de recursos Azure e não-Azure em um único local. É amplamente utilizado para análise de tendências e solução de problemas.
Funcionalidades:
Coleta de Logs em Ambientes Híbridos: Compatível com logs de servidores locais e outras nuvens.
Consultas Personalizadas com KQL: Permite consultas detalhadas para análise e criação de relatórios.
Análise de Desempenho e Segurança: Aplicado em auditorias de segurança e monitoramento de integridade.
### 4. Azure Sentinel
Descrição: É a solução de SIEM (Security Information and Event Management) e SOAR (Security Orchestration Automated Response) da Azure. Focada em segurança, permite detectar e responder a ameaças em toda a infraestrutura.
Funcionalidades:
Análise de Segurança: Identificação e investigação de ameaças em tempo real.
Automação de Respostas: Automatiza respostas para incidentes de segurança com playbooks.
Inteligência contra Ameaças: Integra com feeds de ameaças para melhorar a resposta a ataques.
Integração com Log Analytics: Coleta dados de segurança de várias fontes para análises avançadas.
### 5. Azure Service Health
Descrição: Ferramenta que fornece informações sobre o status dos serviços Azure e alertas de interrupções ou falhas de manutenção que podem impactar os recursos do usuário.
Funcionalidades:
Alertas de Integridade do Serviço: Informa sobre problemas nos serviços Azure que possam afetar os usuários.
Manutenções Planejadas: Atualizações de manutenção programadas e sugestões para minimizar impacto.
Status Regional e Histórico de Incidentes: Permite acompanhar status por região e consultar históricos.
### 6. Azure Advisor
Descrição: O Azure Advisor é uma ferramenta de recomendação que ajuda a otimizar os recursos do Azure com sugestões personalizadas, baseadas nas melhores práticas. Ele examina continuamente o ambiente e gera recomendações em cinco áreas principais: custo, segurança, confiabilidade, desempenho e excelência operacional.
Funcionalidades:
Otimização de Custos: Identifica recursos subutilizados ou dimensionados inadequadamente para ajudar a reduzir custos e otimizar o uso.
Melhoria de Segurança: Trabalha com o Azure Security Center para recomendar práticas de segurança e proteção contra vulnerabilidades.
Aprimoramento de Confiabilidade: Sugere configurações para melhorar a resiliência dos recursos e manter alta disponibilidade.
Desempenho Ideal: Recomenda ajustes para melhorar a performance dos aplicativos e recursos.
Excelência Operacional: Ajuda a aprimorar práticas de gerenciamento e automação, simplificando a operação dos recursos no Azure.
