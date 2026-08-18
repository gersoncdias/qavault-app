# QA Vault

**Capture, organize e compartilhe evidências de testes com mais agilidade.**

O QA Vault é uma solução criada para profissionais de Quality Assurance registrarem evidências de testes de forma rápida, organizada e segura.

Com o aplicativo desktop, a extensão para navegador e a versão web, você pode capturar screenshots, gravar vídeos, proteger informações sensíveis, organizar arquivos em pastas e gerar links para compartilhar em bugs, tarefas, relatórios e canais de comunicação.

[![Microsoft Store](https://img.shields.io/badge/Microsoft%20Store-Disponível-0078D4?logo=microsoft)](https://apps.microsoft.com/detail/9ngvxr352hhq)
[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Disponível-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/qa-vault/pjhjnkkknjfnnjmkbbgnmehjlbnahiml)
[![Site](https://img.shields.io/badge/Site-qavault.com.br-222222)](https://qavault.com.br)
[![Releases](https://img.shields.io/github/v/release/gersoncdias/qavault-app?display_name=tag&include_prereleases)](https://github.com/gersoncdias/qavault-app/releases)

> Este repositório é destinado à distribuição de versões, documentação, suporte e acompanhamento público do QA Vault. O código-fonte principal é mantido em um repositório privado.

## Formas de usar o QA Vault

### Aplicativo desktop

Disponível para Windows e Linux, o aplicativo oferece o fluxo mais completo para captura e gerenciamento de evidências.

### Extensão para navegador

A extensão permite capturar imagens e gravar vídeos diretamente durante a navegação. É possível escolher uma aba, uma janela ou a tela inteira, revisar o resultado e baixar o arquivo localmente. Nas imagens, o editor oferece recorte, pixelização, setas, formas, desenho e texto.

Ao gravar uma aba, a extensão também pode coletar informações técnicas de console e rede sincronizadas com a evidência. O envio ao QA Vault é opcional e utiliza a conta e o Google Drive conectados para gerar um link público.

[Instalar o QA Vault no Chrome](https://chromewebstore.google.com/detail/qa-vault/pjhjnkkknjfnnjmkbbgnmehjlbnahiml)

### Versão web

A versão web permite acessar o QA Vault pelo navegador, realizar uploads e importar evidências produzidas em outros dispositivos, incluindo testes mobile.

[Acessar o site do QA Vault](https://qavault.com.br/)

## Versões atuais

- Aplicativo desktop: **1.2.1**
- Extensão para Chrome: **1.1.0**

As versões públicas e seus instaladores ficam disponíveis nas [releases do GitHub](https://github.com/gersoncdias/qavault-app/releases), na Microsoft Store e na Chrome Web Store.

## Principais recursos

- Captura de screenshots pelo aplicativo desktop
- Gravação de vídeos de evidência
- Captura de imagens de abas, janelas ou da tela inteira pela extensão para Chrome
- Gravação de abas, janelas ou da tela inteira pela extensão
- Coleta de console e tráfego de rede durante gravações de aba
- Preview antes de salvar ou enviar
- Recorte, desenho e anotações em imagens
- Pixelização de informações sensíveis
- Player de vídeo com linha do tempo e controles de avanço e retorno
- Download local de capturas e gravações sem exigir Google Drive
- Upload manual de imagens e vídeos
- Organização de evidências em pastas
- Histórico de evidências recentes
- Geração de links públicos para compartilhamento
- Download de evidências pelos links compartilhados
- Integração com Google Drive
- Conexão de até três contas do Google Drive
- Reconexão de contas de armazenamento quando necessário
- Aplicativo disponível para Windows e Linux
- Upload pela versão web e importação de evidências de testes mobile

## Como funciona

1. Abra o QA Vault no aplicativo desktop, na extensão ou na versão web.
2. Capture uma imagem, grave um vídeo ou envie um arquivo.
3. Revise a evidência e proteja informações sensíveis.
4. Salve o arquivo localmente, se quiser trabalhar sem armazenamento conectado.
5. Para publicar, entre com Google ou código enviado por e-mail e conecte uma conta do Google Drive.
6. Escolha uma pasta e envie a evidência.
7. Gere e copie o link público.
8. Compartilhe o link no Jira, Azure DevOps, Slack, Microsoft Teams ou em outra ferramenta.

## Download

### Windows

A versão recomendada para Windows está disponível na Microsoft Store:

[Baixar pela Microsoft Store](https://apps.microsoft.com/detail/9ngvxr352hhq)

Os instaladores publicados diretamente também podem ser encontrados nas releases:

[Ver releases do QA Vault](https://github.com/gersoncdias/qavault-app/releases)

### Linux

Os pacotes para Linux, incluindo o formato `.deb`, são publicados na página de releases:

[Baixar versão para Linux](https://github.com/gersoncdias/qavault-app/releases)

Consulte também o [guia de instalação no Linux](docs/linux-installation.md).

### Google Chrome

A extensão oficial está disponível na Chrome Web Store:

[Instalar a extensão QA Vault](https://chromewebstore.google.com/detail/qa-vault/pjhjnkkknjfnnjmkbbgnmehjlbnahiml)

## Primeiros passos

Consulte o guia completo:

[Começar a usar o QA Vault](getting-started.md)

##  Contribua com o QA Vault

Você não precisa escrever código para contribuir com o QA Vault.

A comunidade pode ajudar por meio de:

- testes exploratórios;
- validação de novas versões;
- relatos de bugs;
- retestes de correções;
- testes de compatibilidade;
- avaliações de usabilidade e acessibilidade;
- sugestões de melhorias;
- contribuições para a documentação.

As contribuições realizadas por meio de Issues, comentários, Test Reports e Pull Requests ficam registradas publicamente no GitHub e podem fazer parte do histórico de participação do contributor em um projeto real de software.

### Quer participar?

- [Veja como contribuir](CONTRIBUTING.md)
- [Consulte o guia de testes](TESTING.md)
- [Veja as Issues abertas](https://github.com/gersoncdias/qavault-app/issues)

A participação é aberta e espontânea. Não existe quantidade mínima de testes, frequência ou prazo obrigatório.

## Enviar feedback ou reportar um problema

Encontrou um erro, dificuldade de uso ou comportamento inesperado?

Antes de abrir uma nova Issue, consulte o [guia de contribuição](CONTRIBUTING.md) e verifique se já existe um relato semelhante.

[Abra uma Issue](https://github.com/gersoncdias/qavault-app/issues/new) informando, sempre que possível:

- versão do QA Vault;
- forma de acesso utilizada: Desktop, Extensão ou Web;
- sistema operacional e navegador;
- comportamento observado;
- comportamento esperado;
- passos para reprodução;
- prints, vídeos ou links de evidência.

Não publique tokens, senhas, dados pessoais, evidências confidenciais ou informações internas da sua empresa.

Sugestões de funcionalidades e melhorias também são bem-vindas:

[Enviar sugestão](https://github.com/gersoncdias/qavault-app/issues/new)

## Documentação

- [Primeiros passos](getting-started.md)
- [Como contribuir](CONTRIBUTING.md)
- [Guia de testes](TESTING.md)
- [Instalação no Linux](docs/linux-installation.md)
- [Histórico de alterações](CHANGELOG.md)
- [Releases publicadas](https://github.com/gersoncdias/qavault-app/releases)

## Status do projeto

O QA Vault está em evolução contínua. Entre os objetivos planejados estão:

- integração com Playwright e Cypress;
- upload automático de evidências geradas por testes;
- evolução da sincronização dos eventos técnicos com a linha do tempo dos vídeos;
- relatórios e dashboards;
- melhorias de colaboração para times e projetos;
- novas opções de armazenamento.

## Código-fonte

O código-fonte principal, o backend, a infraestrutura e os workflows internos são mantidos em um repositório privado.

Este repositório público contém:

- documentação;
- releases e instaladores;
- notas de versão;
- acompanhamento de bugs;
- solicitações de melhorias;
- ciclos públicos de teste;
- Test Reports e validações da comunidade;
- contribuições de documentação;
- informações públicas do produto.

## Links

- Site: [qavault.com.br](https://qavault.com.br/)
- Extensão para Chrome: [Chrome Web Store](https://chromewebstore.google.com/detail/qa-vault/pjhjnkkknjfnnjmkbbgnmehjlbnahiml)
- Aplicativo para Windows: [Microsoft Store](https://apps.microsoft.com/detail/9ngvxr352hhq)
- Releases: [GitHub Releases](https://github.com/gersoncdias/qavault-app/releases)
- Issues: [GitHub Issues](https://github.com/gersoncdias/qavault-app/issues)

---

Feito para simplificar o registro e o compartilhamento de evidências no dia a dia de QA.
