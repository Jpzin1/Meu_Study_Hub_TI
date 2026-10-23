# Plano de implantação e segurança — Study Hub TI

- Autor: João Pedro Holanda da Costa
- Disciplina: Bootcamp I — CEUB
- Atualização: 23/10/2026
- Status: documentação inicial integrada à main; publicação e testes manuais concluídos. Registro atualizado dos resultados em preparação.

## 1. Objetivo

Documentar a implantação do Study Hub TI, suas configurações de acesso
e segurança, o fluxo de atualização e os procedimentos de teste e manutenção.

O projeto centraliza minha apresentação profissional, atividades acadêmicas
e projetos pessoais e desenvolvidos em equipe.

## 2. Arquitetura e ambiente

O portfólio utiliza HTML, CSS e JavaScript, sem backend, banco de dados
ou cadastro de visitantes no próprio site.

- Código e documentação: GitHub.
- Hospedagem: GitHub Pages.
- Branch de publicação: main.
- Pasta de publicação: raiz do repositório, /(root).
- Site: https://jpzin1.github.io/Meu_Study_Hub_TI/
- Repositório: https://github.com/Jpzin1/Meu_Study_Hub_TI

As configurações de publicação foram verificadas na tela Settings > Pages.
O site foi acessado e utilizado durante os testes manuais.

## 3. Gestão de acesso e segurança

### Configurações verificadas

- O repositório é público.
- Não há colaboradores convidados com acesso direto ao repositório.
- O proprietário gerencia as alterações e as configurações.
- A opção Enforce HTTPS está ativada no GitHub Pages.
- O ruleset Protecao-main está ativo e direcionado à branch main.
- A lista de exceções do ruleset está vazia.

### Regras selecionadas durante a configuração

- Restrict deletions: restringir a exclusão da branch protegida.
- Block force pushes: bloquear sobrescrita forçada do histórico.
- Require a pull request before merging: exigir pull request.
- Required approvals: 0, considerando o desenvolvimento individual.

O autor conferiu o conteúdo da documentação na aba Files changed antes
do merge do PR #2. Essa conferência não equivale a uma aprovação independente.

As configurações foram verificadas pela interface do GitHub. Não foram
executadas tentativas de exclusão ou force push para testar os bloqueios.

### Política de publicação

Publicar somente materiais acadêmicos, pessoais e autorizados.
Não incluir senhas, tokens, credenciais, dados pessoais de terceiros
ou informações internas de empresas e clientes.

O site público não oferece área privada. A gestão de acesso descrita
neste documento refere-se à manutenção do repositório.

## 4. Fluxo de trabalho e colaboração

O fluxo adotado para esta etapa foi:

1. Registrar a tarefa em uma issue.
2. Criar uma branch a partir da main.
3. Elaborar a documentação nessa branch.
4. Registrar as alterações com uma mensagem de commit descritiva.
5. Abrir um pull request direcionado à main.
6. Conferir o conteúdo na aba Files changed.
7. Realizar o merge.
8. Acompanhar a publicação no GitHub Pages.
9. Executar testes manuais no site e preparar o registro dos resultados.

Para alterações futuras no site, executar os testes aplicáveis antes
do merge e repetir as verificações essenciais após a publicação.

### Registros desta atividade

- Issue: https://github.com/Jpzin1/Meu_Study_Hub_TI/issues/1
- Branch utilizada: docs/implantacao-seguranca
- Pull request: https://github.com/Jpzin1/Meu_Study_Hub_TI/pull/2
- Situação do PR #2: integrado à main e encerrado.
- Commit de merge: 061a091.
- Publicação: execução #3 de pages build and deployment.
- Resultado da publicação: concluída com sucesso em 25 segundos.

O PR #2 integrou a versão inicial do plano, ainda com testes pendentes.
Os resultados apresentados nesta atualização foram obtidos posteriormente.

O projeto é individual. O uso de issue, branch e pull request registra
um fluxo de trabalho aplicável à colaboração, sem representar participação
de outro revisor.

## 5. Uso do Google Gemini

O Google Gemini foi consultado para propor um plano de implantação
adequado a um portfólio estático e individual.

Foram solicitadas orientações sobre:

- implantação e arquitetura;
- gestão de permissões e segurança;
- fluxo de branches e pull requests;
- testes e critérios de aceitação;
- recuperação de versões e manutenção;
- organização da documentação com ferramentas do Google.

As respostas foram revisadas antes da adoção. Recomendações da IA
não foram consideradas evidências de configurações ou testes realizados.

### Decisões adotadas

- Manter a arquitetura estática e a hospedagem no GitHub Pages.
- Conferir HTTPS e acesso de colaboradores.
- Configurar proteção para a branch principal.
- Utilizar issue, branch e pull request nesta atividade.
- Executar testes manuais e registrar os resultados observados.
- Planejar a organização do documento final no Google Docs.

Foram corrigidas orientações sobre aprovação do próprio pull request
e recuperação de versões. A conferência do autor não foi tratada como
aprovação independente, e a reversão deve desfazer a alteração problemática.

As respostas do Gemini foram preservadas como referência do planejamento.
A organização dessas evidências no documento final permanece pendente.

## 6. Testes executados e resultados

Data dos testes: 23/10/2026.
Responsável pela execução manual: João Pedro Holanda da Costa.

### Ambientes utilizados

- Computador: Windows com Google Chrome.
- Celular: iPhone com Safari.
- Versões dos navegadores, modelo do iPhone e dimensões exatas da área
  de visualização não foram registrados.

Os resultados abaixo foram registrados a partir das verificações manuais
relatadas pelo autor e das capturas disponibilizadas durante a atividade.

| ID | Verificação | Resultado observado | Situação |
| --- | --- | --- | --- |
| T01 | Acesso ao site | Página carregou e permitiu navegação; HTTPS obrigatório confirmado nas configurações | Aprovado no teste manual |
| T02 | Navegação interna | Todos os itens do menu levaram às seções correspondentes | Aprovado no teste manual |
| T03 | Links externos | Links verificados abriram os destinos esperados; LinkedIn abriu o perfil correto após login | Aprovado no escopo verificado |
| T04 | Layout móvel | Autor confirmou conteúdo legível e organizado no iPhone com Safari | Aprovado no teste manual |
| T05 | Menu móvel | Autor confirmou funcionamento do menu e acesso às seções no iPhone com Safari | Aprovado no teste manual |
| T06 | Layout desktop | Autor percorreu a página e confirmou ausência de cortes e sobreposições | Aprovado no teste manual |
| T07 | Navegação por teclado | Autor confirmou destaque de foco e funcionamento com Tab e Enter | Aprovado no teste manual |
| T08 | Console do navegador | Autor informou ausência de mensagens de erro após recarregar e navegar | Aprovado no teste manual |
| T09 | Publicação após merge | Execução #3 concluída com sucesso; site acessado após a implantação | Aprovado para a implantação do PR #2 |

### Evidências e observações

- Captura das configurações do GitHub Pages com Enforce HTTPS ativado.
- Captura da gestão de acesso sem colaboradores convidados.
- Captura do ruleset ativo e aplicado à main.
- PR #2 com status Merged.
- Captura da execução #3 de publicação concluída com sucesso.
- Captura da página inicial do site em desktop.
- Capturas dos destinos GitHub, Disciplinas e Projetos e Certificados.
- Captura do perfil correto do LinkedIn após autenticação.
- Relatos do autor sobre navegação interna, celular, teclado,
  console e organização visual da página completa.

No LinkedIn, a primeira tentativa exibiu uma tela de entrada.
Após autenticação e novo acesso pelo link do portfólio, o perfil correto
foi exibido. Não foi necessária alteração no link.

A verificação dos links não representa uma auditoria recursiva de todos
os arquivos e repositórios acessíveis a partir do Study Hub.

Os testes foram manuais. Não foram realizadas auditorias automatizadas
de desempenho, acessibilidade ou segurança. Os resultados não garantem
compatibilidade com todos os dispositivos e navegadores.

## 7. Implantação e recuperação

A documentação inicial foi incorporada à main pelo PR #2.
A publicação correspondente do GitHub Pages foi concluída com sucesso
e o site foi acessado após a implantação.

Após novos merges, acompanhar a execução da publicação e verificar
o site antes de considerar a alteração entregue.

Se uma atualização causar problema:

1. Identificar a alteração responsável.
2. Preparar uma reversão por pull request.
3. Conferir o conteúdo da reversão.
4. Realizar o merge e acompanhar a nova publicação.
5. Repetir os testes afetados.

A recuperação deve preservar o histórico do projeto.
Esse procedimento está planejado; não foi realizado um teste de recuperação.

## 8. Cronograma e acompanhamento

| Data | Atividade | Situação |
| --- | --- | --- |
| 23/10/2026 | Consultar o Gemini e elaborar o plano inicial | Concluído |
| 23/10/2026 | Conferir HTTPS e acesso; configurar proteção da main | Concluído |
| 23/10/2026 | Criar issue e branch; revisar e integrar o PR #2 | Concluído |
| 23/10/2026 | Acompanhar a publicação e executar testes manuais | Concluído |
| 23 a 24/10/2026 | Integrar o registro atualizado dos resultados por novo PR | Pendente |
| Até 25/10/2026 | Organizar documento e evidências no Google Docs | Pendente |
| Até 25/10/2026 | Gravar e publicar a apresentação final de 5 minutos | Pendente |
| Até 25/10/2026, às 23h55 | Conferir links, exportar PDF e enviar a entrega | Pendente |

Os testes inicialmente previstos para 24/10 foram antecipados para 23/10.
As atividades pendentes não são apresentadas como concluídas.

## 9. Manutenção

Realizar revisão bimestral e após alterações relevantes.

- Conferir os links.
- Atualizar projetos e informações profissionais.
- Revisar permissões e regras de proteção.
- Executar novamente os testes afetados.
- Registrar alterações no histórico do projeto.
- Registrar data, ambiente e evidências dos novos testes.

## 10. Pendências da entrega final

- Integrar esta atualização dos resultados por novo pull request.
- Conferir a publicação correspondente à atualização.
- Encerrar a issue #1 após concluir seus registros.
- Organizar o documento final e as evidências no Google Docs.
- Gravar e publicar a apresentação final de 5 minutos.
- Inserir os links definitivos e exportar a entrega em PDF.
- Enviar a entrega na plataforma da disciplina.
