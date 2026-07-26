# Changelog

Este documento registra as principais mudanças publicadas no QA Vault.

O projeto segue o padrão de [Versionamento Semântico](https://semver.org/lang/pt-BR/):

* `MAJOR`: mudanças incompatíveis ou que exigem migração.
* `MINOR`: novas funcionalidades compatíveis com versões anteriores.
* `PATCH`: correções, melhorias visuais e ajustes de estabilidade.

As mudanças são organizadas nas categorias:

* **Adicionado**
* **Alterado**
* **Corrigido**
* **Removido**
* **Segurança**

---

### Roadmap

* Novas opções de armazenamento em nuvem.
* Integrações com Playwright e Cypress.
* Upload automático de evidências em pipelines CI/CD.
* Captura de requests, responses e erros de console.
* Sincronização de eventos técnicos com a linha do tempo dos vídeos.

---

## [0.1.6] - 2026-07-21

### Adicionado

* Aplicação web em `/app` para upload e gerenciamento de evidências pelo navegador.
* Login com Google e autenticação por código OTP enviado por e-mail.
* Conexão com Google Drive na versão web.
* Upload de arquivos por seleção ou arrastar e soltar.
* Listagem, exclusão e cópia de links públicos das evidências pelo navegador.
* Suporte à importação de evidências geradas durante testes mobile.
* Abas com contadores separados para imagens e vídeos.
* Paginação  da galeria de evidências.
* Feedback visual após copiar links.
* Botão de acesso ao painel de evidências na página inicial.
* Gravação de vídeos com duração de até cinco minutos.
* Organização de evidências em pastas.
* Ferramenta de corte de imagens.
* Ferramenta de pixelização de informações sensíveis.
* Histórico para desfazer alterações durante a edição.

### Alterado

* Melhorada a qualidade das imagens capturadas.
* Atualizado o fluxo do Google Drive para recarregar automaticamente o status da conexão, licença e evidências após a autorização.
* Ajustado o processo de autenticação para não depender do estado da janela de autorização durante navegações entre domínios.
* Melhorada a experiência de edição e organização das evidências.
* Melhorada a experiência de acesso ao painel em dispositivos móveis.

### Corrigido

* Corrigida a página de conclusão da autorização Google, cujo fechamento automático era bloqueado pela política de segurança do backend.
* Corrigido o fechamento da janela de autorização do Google Drive no navegador e no aplicativo desktop.
* Corrigida a atualização visual da conexão com o Google Drive após o retorno da autorização.
* Corrigida a atualização da lista de evidências após conectar uma conta Google Drive.
* Corrigidos problemas de estabilidade no fluxo de captura e edição.

### Distribuição

* Publicação do QA Vault na Microsoft Store.
* Disponibilização do instalador para Windows.
* Disponibilização do pacote para Linux.
* Publicação de artefatos separados para Windows e Linux.

---

## [0.1.3] - 2026-07-01

### Corrigido

* Corrigido o fluxo de conexão com o Google Drive no Windows.
* A autorização passou a ser reconhecida mesmo quando a janela de autenticação é fechada manualmente após a conclusão.
* Melhorado o tratamento do estado de conexão após o retorno do OAuth.

---

## [0.1.2] - 2026-07-01

### Adicionado

* Página de download com informações sobre licença gratuita e renovação.
* Renovação gratuita da licença por períodos de 30 dias.
* Contadores públicos de downloads para Windows e Linux.
* Histórico de versões separado por sistema operacional.
* Formulário de renovação integrado à página de downloads.

### Alterado

* O workspace de evidências passou a utilizar a conta Google Drive conectada.
* O login do aplicativo passou a ser utilizado apenas para controle de sessão.
* Removido o card lateral de evidências no Google Drive para liberar espaço na interface.
* Simplificado o botão de atualização de evidências, mantendo apenas o ícone e o indicador de carregamento.
* Unificado o fluxo de download e renovação da licença na rota `/download`.
* Reorganizada a página de downloads com informações de licença, ajuda, planos e histórico de versões.
* Bloqueadas as ações de captura, gravação e upload enquanto o Google Drive não estiver conectado.
* Adicionada orientação para conexão com o Google Drive antes da criação de evidências.

### Corrigido

* Corrigido o botão **Abrir painel** da bandeja do sistema.
* O botão passou a abrir o painel principal em vez da área administrativa.
* Corrigido o estado de carregamento do botão de conexão com o Google Drive quando a janela de autenticação é fechada antes da conclusão.

---

## [0.1.0] - 2026-06-28

### Adicionado

* Primeira versão pública do aplicativo desktop QA Vault.
* Captura de screenshots para criação de evidências.
* Gravação de vídeos da tela.
* Upload manual de imagens e vídeos.
* Visualização e listagem de evidências.
* Geração de links públicos para compartilhamento.
* Integração com autenticação de usuários.
* Integração com Google Drive.
* Fluxo de licença gratuita e renovação.
* Aplicativo executado pela bandeja do sistema.
* Preview da evidência antes do envio.
* Painel administrativo para acompanhamento de feedbacks e downloads.
* Gerenciamento de campanhas promocionais.
* Landing page pública.
* Páginas institucionais.
* Blog do QA Vault.
* Área administrativa.

### Infraestrutura

* Backend em Node.js, Express e TypeScript.
* Persistência de metadados no MongoDB.
* Armazenamento de evidências em filesystem.
* Infraestrutura baseada em Docker e Docker Compose.
* Publicação dos serviços por domínio HTTPS.
