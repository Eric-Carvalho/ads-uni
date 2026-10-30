# Relatório PEX — ADS Projeto de Extensão I

Oct 20, 2026 · @Eric Carvalho

Este relatório documenta o Projeto de Extensão I: um sistema web de ordens de serviço e agendamento, desenvolvido para digitalizar a operação de uma microempresa de limpeza e serviços prediais em Canoas/RS.

## Identificação

| Campo | Informação |
| --- | --- |
| Aluno | Éric Gonçalves de Carvalho |
| E-mail (cadastrado na matrícula) | ericgoncalves.br@gmail.com |
| RA (7 dígitos) | \[preencher\] |
| Curso | Análise e Desenvolvimento de Sistemas |
| Disciplina | ADS – Projeto de Extensão I |
| Instituição | Centro Universitário União das Américas Descomplica |
| Organização parceira | JATO Service – Soluções em Limpeza e Serviços Ltda |
| CNPJ | 24.495.005/0001-09 |
| Responsável na organização | Atilas Pedro de Carvalho – Sócio |
| O que a organização faz | Serviços combinados de apoio a edifícios (CNAE 81.11-7-00): limpeza, pintura, manutenção elétrica e paisagismo |
| Onde fica | Rua Flórida, 590, Mato Grande, Canoas/RS |
| Título do projeto | JATO OS: sistema web de ordens de serviço, agenda e checklist digital |
| Público-alvo | Sócio e equipes de campo da empresa; clientes atendidos (lojas, escritórios e condomínios comerciais) |
| ODS selecionada | ODS 8 – Trabalho decente e crescimento econômico |
| Duração | 20/10 a 27/11/2026 (6 semanas) |
| Dedicação | \[preencher\] horas por semana, em \[preencher: dias da semana\]; total na seção 5 |
| Modalidade | Individual |

> Pendência a confirmar antes da entrega: as consultas públicas indicam o CNPJ acima como baixado desde 04/02/2019. O PEX aceita parceria com MEI ou pessoa física, então, se a empresa não estiver ativa, registre a parceria em nome de Atilas Pedro de Carvalho como pessoa física (ou do CNPJ ativo dele) aqui e no termo.

## 1. Contexto

Sou estudante de Análise e Desenvolvimento de Sistemas e apliquei neste projeto os conhecimentos de levantamento de requisitos, desenvolvimento front-end e back-end, banco de dados e experiência do usuário. O objetivo foi levar uma solução digital simples a uma microempresa que ainda controla sua operação de forma manual.

A JATO Service atua em Canoas/RS com serviços combinados de apoio a edifícios: limpeza comercial e pós-obra, pintura, pequenas manutenções elétricas e paisagismo. Atende condomínios comerciais, lojas e escritórios, com equipes que se deslocam até o cliente.

O contato com a empresa foi feito pessoalmente com o sócio Atilas Pedro de Carvalho, que autorizou a realização do projeto por meio de termo de autorização (Anexo A). A apresentação do aluno e da instituição foi feita com a carta de apresentação (Anexo B).

Conhecimentos do curso aplicados:

- Engenharia de requisitos: entrevista, observação e histórias de usuário
- Experiência do usuário: protótipo de telas simples para uso no celular
- Desenvolvimento web: front-end responsivo e API back-end
- Banco de dados: modelagem relacional de clientes, serviços e ordens
- Gestão de projeto: cronograma, metas e indicadores

## 2. Diagnóstico do problema

A empresa controla pedidos, agenda e execução dos serviços por mensagens de WhatsApp, cadernos e planilhas soltas, o que gera atrasos, retrabalho e perda de histórico. O diagnóstico foi feito na visita presencial, por entrevista com o sócio e observação da rotina. Confirmar e ajustar cada ponto abaixo com o que for constatado na visita.

| Problema observado | Efeito na operação |
| --- | --- |
| Pedidos chegam por WhatsApp e telefone, sem registro único | Solicitações esquecidas ou duplicadas |
| Agenda das equipes em caderno ou planilha | Conflito de horários e deslocamentos mal planejados |
| Sem checklist padronizado por tipo de serviço | Qualidade varia entre equipes; retrabalho a pedido do cliente |
| Sem registro fotográfico de antes e depois | Dificuldade para comprovar a execução em reclamações |
| Sem histórico por cliente | Orçamentos e retornos dependem da memória do sócio |

Linha de base a medir na visita (preencher): \[nº de serviços por semana\], \[tempo médio para registrar um pedido\], \[nº de remarcações ou reclamações no último mês\].

O problema é real e proporcional à solução: não se trata de informatizar a empresa inteira, mas de centralizar pedidos, agenda e comprovação da execução.

## 3. Proposta de solução

A proposta é o JATO OS, um sistema web responsivo, usado pelo celular ou computador, que concentra o ciclo do serviço: pedido, agendamento, execução com checklist e fotos, e conclusão com histórico do cliente.

Funcionalidades:

1. Cadastro de clientes e endereços, com histórico de serviços
2. Abertura de ordem de serviço (OS) com tipo de serviço, data, equipe e observações
3. Agenda semanal por equipe, com alerta de conflito de horário
4. Checklist digital por tipo de serviço (limpeza, pintura, elétrica, paisagismo)
5. Fotos de antes e depois anexadas à OS
6. Status da OS: aberta, agendada, em execução, concluída
7. Painel simples com serviços da semana e OS em atraso

Por que esta solução: é de baixo custo, roda em hospedagem gratuita ou barata, não exige instalação e substitui ferramentas que a equipe já usa sem mudar a forma de trabalhar. A entrega é digital; a negociação, as visitas e o treinamento foram presenciais, como pede o PEX.

### Público-alvo e impacto social

O benefício vai além da empresa: as equipes de campo ganham rotina mais organizada e previsível, e os clientes passam a ter comprovação do serviço com checklist e fotos. Para ampliar o impacto à comunidade, recomenda-se \[opcional: apresentar o sistema em uma conversa aberta para outros pequenos prestadores de serviço do bairro e registrar a participação\].

## 4. Objetivos e definição de sucesso

Sucesso = em 2 semanas de uso real (10/11 a 23/11), 100% dos pedidos da empresa registrados no JATO OS e pelo menos 80% das OS concluídas com checklist e fotos.

Objetivo geral: digitalizar o fluxo de ordens de serviço da JATO Service para reduzir esquecimentos, conflitos de agenda e retrabalho.

Objetivos específicos e metas:

| Indicador | Linha de base | Meta | Como medir |
| --- | --- | --- | --- |
| Pedidos registrados no sistema | 0% | 100% no período de uso | OS abertas ÷ pedidos recebidos |
| OS concluídas com checklist e fotos | 0% | ≥ 80% | Relatório de OS concluídas |
| Conflitos de agenda por semana | \[medir na visita\] | Redução de 50% | Alertas de conflito + relato do sócio |
| Reclamações ou retrabalhos por semana | \[medir na visita\] | Redução de 50% | Registro no histórico do cliente |
| Tempo para registrar um pedido | \[medir na visita\] | ≤ 2 minutos | Cronometragem com a equipe |
| Satisfação do responsável | — | Nota ≥ 8 de 10 | Questionário final |

A porcentagem atingida de cada meta é apresentada na seção 7.

## 5. Etapas e plano de ação

O projeto cabe em 6 semanas, de 20/10 a 27/11/2026 (prazo de entrega da disciplina), com 3 visitas presenciais à empresa.

1. **20/10 a 26/10 – Apresentação, acordo e diagnóstico (visita 1).** Entrega da carta de apresentação, assinatura do termo de autorização, entrevista com o sócio, observação da rotina e coleta da linha de base. Registro: foto no local, termo assinado e anotações.
2. **27/10 a 31/10 – Protótipo e validação.** Protótipo das telas no celular, validado com o sócio e um líder de equipe. Registro: prints do protótipo e ajustes pedidos.
3. **01/11 a 08/11 – Desenvolvimento do MVP.** Clientes, OS, agenda, checklist, fotos e painel. Registro: prints de cada tela e do repositório.
4. **09/11 – Implantação e treinamento (visita 2).** Publicação do sistema, cadastro dos clientes atuais e treinamento da equipe. Registro: fotos do treinamento e lista de presença.
5. **10/11 a 23/11 – Uso real e medição.** Duas semanas de uso, ajustes rápidos e coleta dos indicadores. Registro: relatórios do sistema.
6. **24/11 a 27/11 – Encerramento (visita 3) e relatório.** Questionário de satisfação, foto de encerramento, montagem e envio do relatório em PDF. Registro: questionário respondido.

Responsáveis: o aluno conduz todas as etapas; o sócio valida requisitos, aprova o protótipo e acompanha os resultados.

### Registro de carga horária

O manual pede duração e horas dedicadas por semana; preencha com as datas reais e confira a carga horária no plano de ensino (referência: 40 h).

| Data | Atividade | Local | Horas |
| --- | --- | --- | --- |
| \[ \] | Visita 1: apresentação, termo e diagnóstico | Empresa (presencial) | \[ \] |
| \[ \] | Protótipo e validação | Remoto e empresa | \[ \] |
| \[ \] | Desenvolvimento do MVP | Remoto | \[ \] |
| \[ \] | Visita 2: implantação e treinamento | Empresa (presencial) | \[ \] |
| \[ \] | Acompanhamento e medição | Remoto | \[ \] |
| \[ \] | Visita 3: encerramento e questionário | Empresa (presencial) | \[ \] |
|  | **Total** |  | \[ \] |

## 6. Desenvolvimento da solução

O JATO OS foi construído como aplicação web responsiva com API própria e banco relacional, priorizando uso no celular pelas equipes em campo.

### Requisitos principais

| Código | Requisito | Tipo |
| --- | --- | --- |
| RF01 | Cadastrar clientes, endereços e contato | Funcional |
| RF02 | Abrir, editar e mudar o status de uma OS | Funcional |
| RF03 | Agendar OS por equipe e alertar conflito de horário | Funcional |
| RF04 | Preencher checklist conforme o tipo de serviço | Funcional |
| RF05 | Anexar fotos de antes e depois à OS | Funcional |
| RF06 | Exibir histórico de serviços por cliente | Funcional |
| RF07 | Painel com OS da semana e OS em atraso | Funcional |
| RNF01 | Funcionar no navegador do celular, sem instalação | Não funcional |
| RNF02 | Acesso com login e dois perfis: gestor e equipe | Não funcional |
| RNF03 | Custo mensal de hospedagem zero ou mínimo | Não funcional |
| RNF04 | Dados de clientes tratados conforme a LGPD | Não funcional |

### Tecnologias

| Camada | Tecnologia | Motivo |
| --- | --- | --- |
| Front-end | React + CSS responsivo | Telas simples e reutilizáveis para celular |
| Back-end | Node.js + Express (API REST) | Regras de negócio, autenticação e validação |
| Banco de dados | PostgreSQL | Relações entre clientes, OS, equipes e checklists |
| Armazenamento de fotos | Serviço de armazenamento de objetos | Fotos fora do banco, links na OS |
| Hospedagem | Plano gratuito de nuvem | Atende o requisito de custo |
| Versionamento | Git + GitHub | Histórico do desenvolvimento como evidência |

&#91;embedded content: arquitetura do JATO OS · 5 componentes\]

O celular acessa o front-end; toda regra passa pela API, que grava os dados no banco e as fotos no armazenamento.

### Modelo de dados

Entidades: **Cliente** (1:N) **Endereço**; **Cliente** (1:N) **OrdemServico**; **Equipe** (1:N) **OrdemServico**; **TipoServico** (1:N) **ItemChecklist**; **OrdemServico** (1:N) **RespostaChecklist** e **Foto**; **Usuario** com perfil gestor ou equipe.

### Telas (inserir prints)

- &#91;print\] Login
- &#91;print\] Lista e cadastro de clientes
- &#91;print\] Nova OS
- &#91;print\] Agenda semanal com alerta de conflito
- &#91;print\] Checklist e fotos na execução
- &#91;print\] Painel do gestor

## 7. Resultados

&#91;Preencher após o período de uso: uma frase com o resultado principal, por exemplo "No período de 10/11 a 23/11, X% dos pedidos foram registrados no sistema e Y% das OS foram concluídas com checklist e fotos."\]

| Indicador | Linha de base | Meta | Resultado | % da meta |
| --- | --- | --- | --- | --- |
| Pedidos registrados no sistema | 0% | 100% | \[ \] | \[ \] |
| OS concluídas com checklist e fotos | 0% | ≥ 80% | \[ \] | \[ \] |
| Conflitos de agenda por semana | \[ \] | −50% | \[ \] | \[ \] |
| Reclamações ou retrabalhos por semana | \[ \] | −50% | \[ \] | \[ \] |
| Tempo para registrar um pedido | \[ \] | ≤ 2 min | \[ \] | \[ \] |
| Satisfação do responsável | — | ≥ 8/10 | \[ \] | \[ \] |

Outros dados a registrar do sistema: total de OS abertas, total de clientes cadastrados, número de usuários ativos e número de fotos anexadas.

Como calcular % da meta: resultado ÷ meta × 100 para metas de aumento; para metas de redução, redução obtida ÷ redução pretendida × 100.

## 8. Relação com os Objetivos de Desenvolvimento Sustentável

O projeto se enquadra na **ODS 8 – Trabalho decente e crescimento econômico**, a única a selecionar no envio.

- **Meta 8.2** – aumentar a produtividade por meio da modernização tecnológica: o sistema substitui controles manuais e reduz retrabalho.
- **Meta 8.3** – apoiar micro e pequenas empresas: a solução é gratuita para a empresa e adequada ao seu porte.

O problema não é só local: micro e pequenos prestadores de serviço em todo o país operam com controles informais, e uma ferramenta simples de OS é replicável para outros negócios do mesmo tipo.

## 9. Registros e evidências

As evidências abaixo comprovam a visita presencial, a parceria e a execução; insira cada imagem com uma legenda de uma linha e data. O envio não aceita links, então tudo entra como imagem dentro do PDF.

- [ ] Pelo menos duas fotos do aluno no local da empresa, com data (exigência mínima do PEX)
- [ ] Termo de autorização assinado pelo responsável (Anexo A)
- [ ] Carta de apresentação entregue (Anexo B)
- [ ] Foto da entrevista ou da observação da rotina
- [ ] Prints do protótipo e das telas finais do sistema
- [ ] Print do repositório com o histórico de commits
- [ ] Fotos do treinamento da equipe (visita 2) e lista de presença
- [ ] Prints do painel com os números do período de uso
- [ ] Exemplo de OS concluída com checklist e fotos de antes e depois (sem dados pessoais de clientes)
- [ ] Questionário de satisfação respondido e foto de encerramento (visita 3)

Cuidado com a LGPD: borre nomes, telefones e endereços de clientes nos prints.

## 10. Conclusão

&#91;Preencher após a execução: se a meta de sucesso foi atingida, com o número, por exemplo "A meta foi atingida em X%".\]

Roteiro para a conclusão, um parágrafo curto para cada item:

- **Resultado:** o que mudou na operação da empresa, com os números da seção 7.
- **Dificuldades:** por exemplo, adesão da equipe ao celular, internet fraca nos locais de serviço ou ajustes de agenda.
- **Como foram contornadas:** treinamento curto, telas mais simples, registro offline e envio depois.
- **Aprendizados:** levantar requisitos com quem usa, combinar com o cliente o que é sucesso antes de começar, entregar um MVP pequeno e medir.
- **Continuidade:** próximas melhorias possíveis, como orçamento digital, assinatura do cliente na conclusão da OS e relatórios mensais, que podem virar o Projeto de Extensão II com a mesma empresa.

O manual pede desafios, conquistas e aprendizados do estudante **e da organização**: inclua um depoimento curto do responsável sobre o que mudou para a empresa e para as equipes.

## Anexo A – Termo de autorização (minuta)

Minuta para conferência com o modelo oficial da instituição; use o oficial se estiver disponível.

**TERMO DE AUTORIZAÇÃO PARA REALIZAÇÃO DE PROJETO DE EXTENSÃO**

A empresa **JATO Service – Soluções em Limpeza e Serviços Ltda**, inscrita no CNPJ sob o nº **24.495.005/0001-09**, com sede na Rua Flórida, 590, Mato Grande, Canoas/RS, neste ato representada por seu sócio **Atilas Pedro de Carvalho**, AUTORIZA o(a) estudante **Éric Gonçalves de Carvalho**, regularmente matriculado(a) no curso de Análise e Desenvolvimento de Sistemas da UniAmérica Descomplica, RA \[preencher\], a realizar em suas dependências o Projeto de Extensão "JATO OS: sistema web de ordens de serviço, agenda e checklist digital", vinculado à disciplina ADS – Projeto de Extensão I.

A empresa declara estar ciente de que:

1. o projeto tem finalidade acadêmica e extensionista, sem custo e sem vínculo empregatício entre as partes;
2. o(a) estudante poderá visitar a empresa, entrevistar seus responsáveis e registrar o projeto por fotos e capturas de tela;
3. os registros poderão ser usados no relatório acadêmico, preservando dados pessoais de clientes e colaboradores, conforme a LGPD;
4. a autorização pode ser revogada a qualquer tempo, mediante comunicação ao(à) estudante.

Canoas/RS, \_\_\_\_ de \_\_\_\_\_\_\_\_\_\_\_\_\_\_ de 2026.

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\
Atilas Pedro de Carvalho – Sócio\
JATO Service – Soluções em Limpeza e Serviços Ltda

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\
Éric Gonçalves de Carvalho – Estudante

## Anexo B – Carta de apresentação (minuta)

Canoas/RS, \_\_\_\_ de \_\_\_\_\_\_\_\_\_\_\_\_\_\_ de 2026.

À **JATO Service – Soluções em Limpeza e Serviços Ltda**\
A/C Sr. **Atilas Pedro de Carvalho** – Sócio

Prezado senhor,

Apresento o(a) estudante **Éric Gonçalves de Carvalho**, regularmente matriculado(a) no curso superior de Análise e Desenvolvimento de Sistemas da UniAmérica Descomplica, RA \[preencher\].

A extensão universitária é componente obrigatório da formação, conforme as diretrizes do Ministério da Educação, e tem como propósito levar o conhecimento acadêmico à comunidade por meio da solução de problemas reais. Na disciplina ADS – Projeto de Extensão I, o(a) estudante propõe desenvolver, sem custo para a empresa, uma solução digital de apoio à gestão de ordens de serviço.

Solicitamos a gentileza de recebê-lo(a), permitir as visitas necessárias ao diagnóstico e ao acompanhamento do projeto e, se de acordo, assinar o termo de autorização anexo.

Agradecemos a colaboração.

Atenciosamente,

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\
Éric Gonçalves de Carvalho – Estudante de ADS\
UniAmérica Descomplica
