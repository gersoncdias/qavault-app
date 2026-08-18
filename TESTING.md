# Testing QA Vault

Este documento apresenta formas de contribuir com a qualidade do QA Vault por meio de testes nas versões públicas do produto.

Não é necessário conhecimento em programação para participar.

## Produtos que podem ser testados

O QA Vault possui diferentes formas de uso:

* Aplicativo Desktop
* Extensão para navegador
* Versão Web

Cada produto pode possuir comportamentos, limitações e cenários específicos.

## Tipos de teste

Algumas formas de contribuir:

* Testes exploratórios
* Testes funcionais
* Testes de regressão
* Smoke tests
* Testes de compatibilidade
* Testes de usabilidade
* Testes de acessibilidade

Você não precisa executar todos os tipos de teste.

Escolha livremente os cenários que deseja validar.

## Aplicativo Desktop

Sugestões de cenários:

* Instalar e abrir o aplicativo
* Capturar uma screenshot
* Revisar a captura
* Recortar uma imagem
* Pixelizar informações sensíveis
* Fazer anotações na imagem
* Baixar uma captura localmente
* Gravar um vídeo curto
* Finalizar a gravação
* Revisar o vídeo
* Fazer login
* Conectar uma conta de armazenamento
* Fazer upload de uma imagem
* Fazer upload de um vídeo
* Criar ou selecionar uma pasta
* Gerar um link público
* Copiar e abrir o link gerado
* Consultar evidências recentes

## Extensão para navegador

Sugestões de cenários:

* Instalar a extensão
* Abrir a extensão pelo navegador
* Capturar uma aba
* Capturar uma janela
* Capturar a tela inteira
* Cancelar o seletor de captura
* Realizar uma nova captura após cancelamento
* Editar uma imagem capturada
* Recortar a imagem
* Adicionar anotações
* Pixelizar informações sensíveis
* Copiar a captura
* Baixar a captura localmente
* Conectar a extensão ao QA Vault
* Enviar uma evidência
* Gravar um vídeo de uma aba
* Gravar uma janela
* Gravar a tela inteira
* Cancelar uma gravação
* Revisar o arquivo gerado
* Validar informações técnicas associadas à evidência
* Validar comportamentos em páginas protegidas pelo navegador

## Versão Web

Sugestões de cenários:

* Acessar a aplicação pelo navegador
* Fazer login
* Fazer upload de imagem
* Fazer upload de vídeo
* Importar evidências produzidas em outros dispositivos
* Visualizar uma evidência
* Gerar um link público
* Abrir um link compartilhado
* Baixar uma evidência

## O que observar durante os testes

Durante a execução, observe principalmente:

* clareza das mensagens;
* facilidade para concluir o fluxo;
* comportamento após cancelamentos;
* tratamento de erros;
* qualidade das imagens;
* qualidade dos vídeos;
* tempo de carregamento;
* tempo de upload;
* funcionamento dos links compartilhados;
* comportamento em diferentes navegadores;
* comportamento em diferentes sistemas operacionais;
* presença de informações sensíveis.

## Encontrou um problema?

Antes de abrir uma nova Issue:

1. Pesquise as Issues existentes.
2. Verifique se o problema já foi reportado.
3. Caso exista, adicione informações relevantes ao relato existente.
4. Caso não exista, abra um novo Bug Report.

Um bom Bug Report deve informar:

* produto;
* versão;
* sistema operacional;
* navegador;
* pré-condições;
* passos para reprodução;
* resultado atual;
* resultado esperado;
* frequência;
* evidências.

Consulte também o `CONTRIBUTING.md`.

## Community Testing

Algumas versões poderão possuir ciclos públicos de validação identificados como:

`Community Testing`

Exemplo:

`[Community Testing] QA Vault Extension v1.3.0`

Cada ciclo poderá apresentar:

* escopo sugerido;
* funcionalidades novas;
* áreas que precisam de maior validação;
* ambientes de interesse;
* possíveis riscos conhecidos.

A participação é livre.

Você pode escolher qualquer cenário e registrar seus resultados.

## Test Reports

Mesmo quando nenhum bug é encontrado, o resultado de uma execução pode ajudar o projeto.

Um Test Report pode informar:

### Ambiente

* Produto:
* Versão:
* Sistema operacional:
* Navegador:

### Cenários executados

* [ ] Cenário 1
* [ ] Cenário 2
* [ ] Cenário 3

### Bugs encontrados

Informe as Issues relacionadas, caso existam.

Exemplo:

`#123`

### Resultado geral

Exemplos:

* Aprovado
* Aprovado com observações
* Reprovado
* Não concluído

## Retestes

Quando uma Issue possuir a label:

`ready-for-retest`

uma correção está disponível para nova validação.

Ao realizar o reteste, informe:

* versão utilizada;
* ambiente;
* passos executados;
* resultado;
* evidência, quando necessário.

Exemplo:

### Reteste

Versão: 1.3.1
Sistema: Windows 11
Navegador: Chrome

Resultado:

* [x] Problema não reproduzido
* [x] Fluxo principal funcionando
* [x] Não foram encontradas regressões relacionadas

Resultado geral: aprovado.

## Dados de teste e privacidade

Nunca utilize dados confidenciais ou informações reais de clientes em contribuições públicas.

Não publique:

* senhas;
* tokens;
* cookies;
* chaves de API;
* documentos pessoais;
* informações internas de empresas;
* URLs internas;
* evidências corporativas confidenciais.

Utilize somente ambientes e massas de teste autorizados.

Para questões relacionadas a segurança, consulte `SECURITY.md`.

## Participação

Não existe quantidade mínima de cenários, frequência ou prazo obrigatório.

Você pode participar quando quiser e escolher livremente o que deseja testar.

Cada contribuição ajuda a melhorar o QA Vault.
