# Plano de implantação e segurança — Study Hub TI

Autor: João Pedro Holanda da Costa
Disciplina: Bootcamp I — CEUB
Data: 23/10/2026
Status: documentação em elaboração; testes e integração por pull request pendentes.

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

A revisão das alterações será realizada pelo próprio autor antes do merge.
Essa conferência não equivale a uma aprovação independente.

### Política de publicação

Publicar somente materiais acadêmicos, pessoais e autorizados.
Não incluir senhas, tokens, credenciais, dados pessoais de terceiros
ou informações internas de empresas e clientes.

O site público não oferece área privada. A gestão de acesso descrita
neste documento refere-se à manutenção do repositório.

## 4. Fluxo de trabalho e colaboração

O fluxo adotado para esta etapa é:

1. Registrar a tarefa em uma issue.
2. Criar uma branch a partir da main.
3. Elaborar e conferir as alterações nessa branch.
4. Registrar as alterações com uma mensagem de commit descritiva.
5. Abrir um pull request direcionado à main.
6. Revisar os arquivos alterados e os resultados dos testes aplicáveis.
7. Realizar o merge.
8. Conferir o resultado da publicação no GitHub Pages.

### Registros desta atividade

- Issue: https://github.com/Jpzin1/Meu_Study_Hub_TI/issues/1
- Branch: docs/implantacao-seguranca
- Pull request: ainda não criado.
- Merge e verificação da publicação: pendentes.

O projeto é individual. O uso de issue, branch e pull request registra
um processo de colaboração, sem representar participação de outro revisor.

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

### Decisões tomadas

- Manter a arquitetura estática e a hospedagem no GitHub Pages.
- Conferir HTTPS e acesso de colaboradores.
- Configurar proteção para a branch principal.
- Utilizar issue, branch e pull request nesta atividade.
- Registrar testes com resultados reais.
- Manter pendente a organização do documento final no Google Docs.

As conversas com o Gemini serão preservadas como evidência do apoio
da ferramenta durante o planejamento.

## 6. Plano de testes

Os testes abaixo ainda precisam ser executados.
A publicação do site, por si só, não comprova sua aprovação.

| ID | Verificação | Critério de aceitação | Situação |
| --- | --- | --- | --- |
| T01 | Acesso ao site | Página abre por HTTPS e carrega seus recursos | Pendente |
| T02 | Navegação interna | Links do menu levam às seções corretas | Pendente |
| T03 | Links externos | Destinos correspondem aos projetos e perfis indicados | Pendente |
| T04 | Layout móvel | Conteúdo legível, sem sobreposição ou rolagem horizontal indevida | Pendente |
| T05 | Menu móvel | Abre, fecha e permite acessar as seções | Pendente |
| T06 | Layout desktop | Conteúdo e navegação permanecem organizados | Pendente |
| T07 | Navegação por teclado | Links e botões acessíveis, com foco visível | Pendente |
| T08 | Console do navegador | Ausência de erros atribuíveis ao código do site durante a navegação | Pendente |
| T09 | Publicação após merge | Implantação concluída e conteúdo atualizado disponível | Pendente |

Para cada teste, registrar data, navegador, tamanho de tela quando
aplicável, resultado e evidência. Caso ocorra falha, registrar a correção
e executar novamente o teste afetado.

## 7. Implantação e recuperação

Após o merge na main, acompanhar a execução da publicação do GitHub Pages
e verificar o site antes de considerar a alteração entregue.

Se uma atualização causar problema:

1. Identificar a alteração responsável.
2. Preparar uma reversão por pull request.
3. Conferir o conteúdo da reversão.
4. Realizar o merge e acompanhar a nova publicação.
5. Repetir os testes afetados.

A recuperação deve preservar o histórico do projeto.
Esse procedimento está planejado; não foi realizado um teste de recuperação.

## 8. Cronograma previsto

| Data | Atividade |
| --- | --- |
| 23/10/2026 | Consultar o Gemini, verificar acesso e HTTPS, configurar proteção e elaborar documentação |
| 24/10/2026 | Executar testes, registrar evidências, corrigir problemas e integrar as alterações por pull request |
| 25/10/2026 | Finalizar o documento, gravar a apresentação de 5 minutos, conferir os links e enviar o PDF até 23h55 |

O cronograma representa o planejamento, não a confirmação de conclusão
das atividades.

## 9. Manutenção

Realizar revisão bimestral e após alterações relevantes.

- Conferir os links.
- Atualizar projetos e informações profissionais.
- Revisar permissões e regras de proteção.
- Executar novamente os testes afetados.
- Registrar alterações no histórico do projeto.

## 10. Pendências da entrega final

- Executar os testes e preencher seus resultados.
- Criar e revisar o pull request desta documentação.
- Registrar o merge e conferir a publicação.
- Organizar o documento final e as evidências no Google Docs.
- Gravar e publicar a apresentação final de 5 minutos.
- Inserir os links definitivos e exportar a entrega em PDF.
