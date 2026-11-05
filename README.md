# PROMPT ÚNICO — Plataforma Inteligente de Matchmaking de Vagas com IA

## 1. CONTEXTO E VISÃO DO PRODUTO

Quero criar uma plataforma web completa de empregabilidade com Inteligência Artificial, desenvolvida integralmente dentro do Lovable.

O objetivo é conectar profissionais às oportunidades de emprego mais compatíveis com seus perfis e utilizar IA para criar versões personalizadas de seus currículos, otimizadas para cada vaga e compatíveis com sistemas ATS (Applicant Tracking Systems).

A plataforma deve funcionar como um assistente inteligente de carreira, acompanhando o usuário desde a análise do currículo até a identificação de oportunidades, personalização do currículo e preparação para candidaturas.

O produto deve ter aparência de uma startup SaaS moderna, premium, intuitiva e profissional.

**IMPORTANTE: NÃO IMPLEMENTAR LOGIN, CADASTRO OU AUTENTICAÇÃO.**

Quero uma experiência de acesso imediato, sem exigir e-mail, senha, criação de conta ou preenchimento de onboarding.

O usuário deve entrar diretamente na plataforma e conseguir executar as funcionalidades principais.

O fluxo principal será:

1. Usuário acessa a plataforma.
2. Faz upload do currículo ou informa suas experiências profissionais.
3. Informa a vaga desejada ou seleciona uma oportunidade disponível.
4. A IA analisa a compatibilidade.
5. A IA gera uma versão personalizada do currículo para aquela vaga.
6. O usuário revisa e baixa o documento.

Toda a aplicação deve ser construída e executada dentro do ecossistema Lovable, utilizando seus recursos nativos de backend, banco de dados, armazenamento e inteligência artificial disponíveis.

Não quero depender de desenvolvimento externo para operar o MVP.

## 2. IDENTIDADE VISUAL E DESIGN SYSTEM

Utilize obrigatoriamente o **shadcn/ui como design system principal**, respeitando seus padrões de componentes, acessibilidade, consistência visual e organização.

### Paleta de cores

A identidade visual deve transmitir tecnologia, confiança, inteligência, sofisticação e oportunidade.

- Azul-claro: `#A9D6F5` — cor de destaque e identidade principal.
- Azul profundo: `#23466B` — títulos, textos de destaque e elementos de navegação.
- Branco: `#FFFFFF` — fundos e superfícies principais.
- Dourado: `#D4AF62` — detalhes premium, indicadores e elementos especiais.
- Cinza-claro: `#F4F7FA` — fundos secundários.
- Cinza-escuro: `#344054` — textos e informações.

### Diretrizes de interface

- Design minimalista, elegante e moderno.
- Layout limpo, com excelente hierarquia visual.
- Bordas arredondadas e sombras suaves.
- Cards com informações bem organizadas.
- Ícones Lucide.
- Tipografia moderna e legível.
- Microinterações e animações sutis.
- Gráficos e indicadores visuais.
- Responsividade completa para desktop, tablet e mobile.
- Utilizar componentes shadcn/ui em botões, inputs, formulários, modais, tabelas, abas, dropdowns, cards, tooltips e navegação.

O dourado deve ser utilizado com moderação para transmitir exclusividade, especialmente em recursos de IA e indicadores de alto potencial de match.

## 3. ESTRUTURA DA PLATAFORMA

Criar as seguintes áreas:

1. Landing Page.
2. Área principal de execução.
3. Dashboard de resultados da análise.
4. Análise de Compatibilidade.
5. Matchmaking de Vagas.
6. Gerador de Currículos com IA.
7. Biblioteca temporária de Currículos.
8. Preparação para Entrevistas.
9. Configurações e Preferências.

A navegação deve ser simples e direta, priorizando a execução imediata da funcionalidade principal.

Não criar páginas de login, cadastro, recuperação de senha ou onboarding obrigatório.

## 4. LANDING PAGE

Criar uma página inicial com visual premium e foco em conversão.

Headline principal:

"Seu próximo emprego começa com o match certo."

Subheadline:

"Encontre oportunidades compatíveis com seu perfil e transforme seu currículo com Inteligência Artificial para conquistar mais entrevistas."

Botão principal:

"Analisar meu currículo"

Ao clicar, o usuário deve ser direcionado diretamente à área de execução da plataforma.

Apresentar três benefícios principais:

**Match inteligente:** encontre vagas alinhadas às suas experiências, habilidades e objetivos.

**Currículo ATS com IA:** personalize seu currículo para cada oportunidade, destacando as competências mais relevantes.

**Carreira organizada:** acompanhe suas análises e descubra como melhorar sua empregabilidade.

Adicionar uma seção explicando como funciona em três etapas:

1. Envie seu currículo.
2. Escolha ou informe a vaga desejada.
3. Gere um currículo personalizado e otimizado para ATS.

Adicionar uma seção com demonstração visual da plataforma, exemplos ilustrativos claramente identificados e CTA final.

## 5. ÁREA PRINCIPAL DE EXECUÇÃO

Esta deve ser a principal tela da aplicação.

O usuário não deve precisar criar conta ou preencher diversos formulários para começar.

Criar uma interface centralizada com dois caminhos de utilização:

### Opção A — Tenho uma vaga específica

Permitir que o usuário:

- Faça upload do currículo em PDF ou DOCX.
- Cole a descrição da vaga.
- Informe a URL da oportunidade, quando disponível.
- Clique em "Analisar compatibilidade".

### Opção B — Quero encontrar vagas compatíveis

Permitir que o usuário:

- Faça upload do currículo em PDF ou DOCX.
- Informe o cargo desejado.
- Escolha a área de atuação.
- Informe a localidade.
- Escolha o modelo de trabalho: remoto, híbrido ou presencial.
- Informe a senioridade desejada.
- Clique em "Encontrar vagas para mim".

O sistema deverá extrair automaticamente as informações do currículo para evitar que o usuário precise preencher tudo manualmente.

### Importação de currículo

A IA deverá:

- Extrair as informações do documento.
- Identificar experiências profissionais.
- Identificar habilidades técnicas e comportamentais.
- Identificar formação e certificações.
- Identificar idiomas.
- Organizar os dados para análise.
- Permitir edição manual antes de prosseguir.

Não inventar experiências, certificações, habilidades ou informações pessoais.

## 6. DASHBOARD DE RESULTADOS

Após a execução da análise, apresentar um dashboard moderno com os resultados.

Exibir:

- Nome do profissional, quando identificado no currículo.
- Cargo atual.
- Cargo desejado.
- Percentual de preenchimento das informações profissionais identificadas.
- Quantidade de vagas analisadas.
- Quantidade de vagas com alto match.
- Compatibilidade geral com a oportunidade selecionada.
- Principais competências identificadas.

Criar uma seção chamada "Oportunidades compatíveis", apresentando vagas recomendadas pela IA.

Cada vaga deve possuir:

- Nome da empresa.
- Cargo.
- Localidade.
- Modelo de trabalho.
- Faixa salarial, quando disponível.
- Data de publicação, quando disponível.
- Link para candidatura.
- Percentual de compatibilidade.
- Botão "Analisar vaga".
- Botão "Criar currículo para esta vaga".

Adicionar um gráfico com os resultados das análises e um painel de atividades da sessão atual.

Não exigir conta para visualizar esses resultados.

## 7. MATCHMAKING INTELIGENTE DE VAGAS

Esta é uma das funcionalidades mais importantes da plataforma.

Criar um mecanismo de matchmaking que compare o currículo e o perfil profissional extraído com vagas de emprego disponíveis.

O sistema deve considerar:

- Experiência profissional.
- Competências técnicas.
- Competências comportamentais.
- Formação acadêmica.
- Idiomas.
- Senioridade.
- Cargo desejado.
- Localidade.
- Modelo de trabalho.
- Pretensão salarial, quando informada.
- Segmento de atuação.

### Algoritmo de compatibilidade

Criar um score de compatibilidade de 0 a 100%.

Utilizar a seguinte distribuição inicial:

- Compatibilidade de habilidades técnicas: 30%.
- Experiência profissional: 25%.
- Senioridade: 15%.
- Formação e certificações: 10%.
- Idiomas: 5%.
- Localização e modelo de trabalho: 10%.
- Preferências salariais: 5%.

O resultado deve apresentar:

**Match de 90% a 100%:** excelente compatibilidade.

**Match de 75% a 89%:** alta compatibilidade.

**Match de 60% a 74%:** compatibilidade moderada.

**Match abaixo de 60%:** baixa compatibilidade.

Não apresentar o score como garantia de contratação ou aprovação.

### Análise explicativa do match

Ao clicar em uma vaga, apresentar:

- Por que essa vaga combina com o profissional.
- Quais competências atendem aos requisitos.
- Quais experiências são relevantes.
- Quais requisitos ainda não são atendidos.
- Quais habilidades poderiam ser desenvolvidas.
- Quais palavras-chave devem aparecer no currículo.

Criar também filtros por:

- Cargo.
- Empresa.
- Localidade.
- Remoto, híbrido ou presencial.
- Senioridade.
- Salário.
- Percentual de match.
- Data de publicação.

### Origem das vagas

Preparar uma arquitetura que permita receber vagas por integrações com APIs e fontes externas autorizadas.

Não criar vagas fictícias apresentadas como oportunidades reais.

Cada oportunidade deve possuir fonte, URL original e data de atualização.

Quando não houver integração disponível, permitir que o usuário cole a descrição da vaga ou informe sua URL para análise pela IA.

## 8. GERADOR DE CURRÍCULOS COM INTELIGÊNCIA ARTIFICIAL

Esta é a principal funcionalidade diferencial do produto.

O usuário poderá selecionar qualquer vaga e clicar em:

"Gerar currículo otimizado para esta vaga".

A IA deverá analisar simultaneamente:

1. O currículo original do usuário.
2. O perfil profissional extraído.
3. A descrição completa da vaga.
4. Os requisitos obrigatórios.
5. Os requisitos desejáveis.
6. As palavras-chave utilizadas pela empresa.
7. As competências mais importantes para a posição.

A partir disso, deverá gerar uma nova versão do currículo, direcionada especificamente àquela oportunidade.

### Regras de otimização ATS

O currículo deve:

- Utilizar estrutura simples e profissional.
- Priorizar layouts de uma coluna.
- Evitar tabelas, gráficos, imagens e elementos que dificultem a leitura por ATS.
- Utilizar títulos convencionais de seções.
- Destacar palavras-chave relevantes da vaga.
- Utilizar termos técnicos adequados.
- Organizar experiências em ordem cronológica inversa.
- Priorizar resultados e conquistas profissionais.
- Utilizar linguagem objetiva e profissional.
- Evitar informações irrelevantes.
- Ser compatível com sistemas de leitura automatizada.
- Manter boa legibilidade para recrutadores humanos.

### Personalização inteligente

A IA poderá:

- Reescrever o resumo profissional.
- Reorganizar competências.
- Melhorar a descrição das experiências.
- Destacar resultados relevantes.
- Adequar a linguagem à senioridade da vaga.
- Sugerir palavras-chave ausentes.
- Recomendar melhorias no conteúdo.

**REGRA FUNDAMENTAL:** nunca inventar experiências, empresas, cargos, datas, resultados, números, certificações, idiomas ou competências que o usuário não informou.

A IA poderá sugerir como melhorar uma informação, mas deverá sinalizar qualquer conteúdo que precise de confirmação do usuário.

### Comparação entre currículos

Criar uma tela comparativa:

- Currículo original.
- Currículo otimizado.
- Alterações realizadas pela IA.
- Palavras-chave adicionadas.
- Competências destacadas.
- Informações que precisam de confirmação.

O usuário deverá poder editar livremente o resultado antes de aprová-lo.

### Exportação

Permitir:

- Visualizar currículo.
- Editar currículo.
- Salvar versão durante a sessão.
- Baixar em PDF.
- Baixar em DOCX.
- Criar novas versões para outras vagas.

Cada currículo deverá ficar vinculado à vaga para a qual foi desenvolvido.

## 9. BIBLIOTECA DE CURRÍCULOS

Criar uma área para organizar todas as versões geradas durante a sessão.

Exibir:

- Nome da vaga.
- Empresa.
- Data de criação.
- Score de compatibilidade.
- Status: Rascunho, Revisado ou Aprovado.
- Botão para visualizar.
- Botão para editar.
- Botão para baixar.

Permitir duplicar, renomear e excluir versões.

Não exigir cadastro para utilizar essa funcionalidade.

Manter os dados temporariamente durante a sessão do navegador, permitindo que o usuário consulte suas análises e versões enquanto estiver utilizando a plataforma.

## 10. PREPARAÇÃO PARA ENTREVISTAS COM IA

Criar uma funcionalidade em que o usuário possa selecionar uma vaga e solicitar uma preparação personalizada.

A IA deverá gerar:

- Perguntas prováveis da entrevista.
- Perguntas técnicas relacionadas à vaga.
- Perguntas comportamentais.
- Sugestões de respostas baseadas na experiência real do usuário.
- Pontos fortes que devem ser destacados.
- Pontos que precisam de preparação.
- Sugestões de perguntas para fazer ao recrutador.

Permitir simulação de entrevista em formato de chat.

## 11. AGENTE DE CARREIRA COM IA

Adicionar um assistente de IA dentro da plataforma.

Nome sugerido: Career AI.

O assistente deverá utilizar o currículo enviado, os resultados das análises e a descrição das vagas da sessão atual como contexto.

Exemplos de perguntas:

- Quais vagas combinam mais comigo?
- Por que meu currículo não está sendo selecionado?
- Quais habilidades preciso desenvolver para chegar a uma posição sênior?
- Como posso melhorar meu LinkedIn?
- Meu currículo está adequado para essa vaga?
- Quais palavras-chave estão faltando?
- Como posso me destacar em uma entrevista?

O assistente deverá fornecer respostas contextualizadas, práticas e baseadas nas informações disponíveis.

## 12. BANCO DE DADOS E BACKEND

Utilizar Lovable Cloud como infraestrutura principal, incluindo banco de dados, armazenamento e recursos de backend disponíveis.

Como a aplicação não terá login ou autenticação, estruturar os dados para permitir o funcionamento sem identificação obrigatória do usuário.

Entidades sugeridas:

- job_opportunities.
- job_requirements.
- job_matches.
- resume_sessions.
- resumes.
- resume_versions.
- ai_interactions.
- interview_preparations.

Criar relacionamentos adequados entre as entidades.

Implementar:

- Processamento seguro de documentos.
- Armazenamento temporário de arquivos.
- Isolamento dos dados por sessão.
- Identificadores temporários de sessão.
- Proteção de informações pessoais.
- Políticas de acesso e segurança (RLS), sem exposição pública indevida de dados.
- Validação de formulários.
- Tratamento de erros.
- Estados de carregamento.
- Feedback visual de sucesso e falha.

Não permitir que usuários acessem documentos, currículos ou análises de outras sessões.

Não criar tabelas ou fluxos de autenticação de usuários.

## 13. INTELIGÊNCIA ARTIFICIAL E INTEGRAÇÕES

Utilizar os recursos de IA disponíveis no Lovable para implementar:

- Extração e interpretação de currículos.
- Análise semântica de vagas.
- Cálculo de compatibilidade.
- Geração de currículos personalizados.
- Identificação de palavras-chave ATS.
- Preparação para entrevistas.
- Assistente de carreira.

Centralizar as instruções de IA para manter consistência e reduzir respostas inventadas.

Utilizar processamento seguro no backend, sem expor chaves de API no frontend.

Toda funcionalidade deve possuir tratamento de falhas e possibilidade de revisão humana.

## 14. EXPERIÊNCIA DO USUÁRIO

A navegação principal deverá utilizar um menu lateral ou navegação simplificada com:

- Início.
- Encontrar vagas.
- Analisar currículo.
- Gerar currículo ATS.
- Minhas versões.
- Preparação para entrevistas.
- Career AI.

Criar uma experiência intuitiva, evitando excesso de informações na mesma tela.

Utilizar indicadores visuais para destacar:

- Alto potencial de match.
- Competências compatíveis.
- Competências ausentes.
- Currículos pendentes de revisão.
- Novas oportunidades.

Adicionar notificações dentro da plataforma durante a sessão.

## 15. REGRAS IMPORTANTES DE DESENVOLVIMENTO

- Construir uma aplicação funcional, não apenas um protótipo visual.
- Não implementar login.
- Não implementar cadastro.
- Não exigir e-mail ou senha.
- Não criar onboarding obrigatório.
- Não utilizar dados fictícios como se fossem dados reais.
- Não criar botões sem funcionalidade.
- Todos os formulários devem executar suas ações corretamente.
- Implementar persistência temporária das análises durante a sessão.
- Implementar estados de loading, vazio, sucesso e erro.
- Garantir responsividade.
- Utilizar componentes shadcn/ui.
- Priorizar acessibilidade e usabilidade.
- Garantir consistência visual entre todas as páginas.
- Não deixar funcionalidades importantes apenas como placeholders.
- Caso uma integração externa dependa de credenciais, criar a estrutura de integração e apresentar claramente o que precisa ser configurado.
- Não simular uma integração como se estivesse funcionando.
- Permitir que o usuário comece a utilizar o produto imediatamente após acessar o endereço da plataforma.

## 16. PRIVACIDADE E SESSÕES TEMPORÁRIAS

Como não haverá autenticação, implementar cuidados específicos:

- Não expor currículos enviados publicamente.
- Não utilizar URLs públicas permanentes para documentos privados.
- Utilizar identificadores de sessão temporários.
- Permitir excluir os arquivos e resultados da sessão.
- Limpar arquivos temporários conforme política de retenção definida.
- Informar ao usuário como seus documentos são processados.
- Não reutilizar currículos para treinar modelos ou finalidades não autorizadas.

Exibir um aviso de privacidade próximo ao upload do currículo.

## 17. RESULTADO ESPERADO

Quero uma plataforma SaaS completa, com aparência de produto comercial pronto para evoluir e escalar.

O usuário deverá conseguir:

1. Acessar a plataforma sem login.
2. Enviar seu currículo.
3. Informar uma vaga ou buscar oportunidades.
4. Receber recomendações de vagas.
5. Visualizar o percentual de compatibilidade.
6. Entender seus pontos fortes e lacunas.
7. Selecionar uma vaga.
8. Gerar um currículo personalizado com IA.
9. Comparar o currículo original com a nova versão.
10. Editar e aprovar o documento.
11. Exportar o currículo em PDF ou DOCX.
12. Consultar as versões criadas durante a sessão.
13. Preparar-se para entrevistas.

**PRIORIDADE MÁXIMA:** o matchmaking de vagas e a geração de currículos personalizados e otimizados para ATS devem ser o coração da plataforma.

A experiência inicial deve ser extremamente simples: entrar, enviar currículo, escolher a vaga e executar.

Não implementar login, cadastro ou autenticação nesta primeira versão. A possibilidade de criar contas e salvar históricos permanentemente poderá ser considerada em uma evolução futura.

O resultado deve transmitir a sensação de estar utilizando um produto de tecnologia premium, com uma experiência visual sofisticada em azul-claro, branco e dourado, navegação simples e inteligência artificial realmente útil.

Construa o produto de forma integrada, com arquitetura organizada, componentes reutilizáveis e funcionalidades reais.

## Evidencia da Execução:

<img width="1078" height="579" alt="Captura de tela 2026-11-05 095136" src="https://github.com/user-attachments/assets/1f3cfd07-6e73-44c3-a649-edb085cbea6b" />
<img width="1083" height="530" alt="Captura de tela 2026-11-05 095123" src="https://github.com/user-attachments/assets/9e2b2fde-eb86-438a-bc09-d89964021ffd" />
<img width="1076" height="536" alt="Captura de tela 2026-11-05 095116" src="https://github.com/user-attachments/assets/ad5d46b6-e7e2-464c-b13c-65984929b3dc" />
<img width="1089" height="547" alt="Captura de tela 2026-11-05 095106" src="https://github.com/user-attachments/assets/e813baa8-18db-4b2e-b541-d24cceffb4c0" />
<img width="1057" height="536" alt="Captura de tela 2026-11-05 095051" src="https://github.com/user-attachments/assets/f8f5bffa-c3c8-4991-98e7-2f2b93e5725d" />
<img width="1081" height="534" alt="Captura de tela 2026-11-05 092731" src="https://github.com/user-attachments/assets/ca5a20c3-a3e8-45a1-bef7-2083d406f4b9" />
<img width="1085" height="541" alt="Captura de tela 2026-11-05 092717" src="https://github.com/user-attachments/assets/6c35a413-ac9f-45c8-9047-ee3baa80ac38" />
<img width="1084" height="544" alt="Captura de tela 2026-11-05 092710" src="https://github.com/user-attachments/assets/5c457ec7-230d-42cf-a9e5-d62a2f5533b1" />
<img width="1084" height="545" alt="Captura de tela 2026-11-05 092653" src="https://github.com/user-attachments/assets/21c8ede2-18f1-4537-ba59-11fe2988f209" />
<img width="1091" height="541" alt="Captura de tela 2026-11-05 092641" src="https://github.com/user-attachments/assets/153bc019-88e1-4811-8760-5d22048013c0" />
<img width="922" height="843" alt="Captura de tela 2026-11-03 151515" src="https://github.com/user-attachments/assets/c1a39d2e-4c3a-4d6c-ba72-026fb944d891" />
<img width="934" height="764" alt="Captura de tela 2026-11-03 151427" src="https://github.com/user-attachments/assets/a9ea14a1-6fe0-4372-9b9e-85458839f30d" />
<img width="945" height="846" alt="Captura de tela 2026-11-03 151420" src="https://github.com/user-attachments/assets/30674ffd-6a59-4992-8eb1-b7ae4342d141" />
<img width="933" height="847" alt="Captura de tela 2026-11-03 133338" src="https://github.com/user-attachments/assets/e43c0805-5b27-4725-9426-38f0fa00f020" />
<img width="936" height="852" alt="Captura de tela 2026-11-03 133333" src="https://github.com/user-attachments/assets/0e240824-8531-427a-a016-4be0f7c104db" />
<img width="926" height="841" alt="Captura de tela 2026-11-03 133326" src="https://github.com/user-attachments/assets/1a2a1cca-b6f7-4be9-b775-00f2963bc6cd" />
<img width="1082" height="545" alt="Captura de tela 2026-11-05 095225" src="https://github.com/user-attachments/assets/7628c889-6d0c-4f38-b3c2-90c43a7d00fd" />
<img width="1077" height="538" alt="Captura de tela 2026-11-05 095155" src="https://github.com/user-attachments/assets/cdc93fc0-9533-458a-8d37-3744cf864375" />
<img width="1069" height="529" alt="Captura de tela 2026-11-05 095146" src="https://github.com/user-attachments/assets/bdf6cd33-bcc8-486b-9f98-48cbab0dc99b" />
