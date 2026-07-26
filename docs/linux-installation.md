# Instalação no Linux

## Pacotes disponíveis

As versões para Linux são publicadas na página de releases:

https://github.com/gersoncdias/qavault-app/releases

O formato principal é o pacote `.deb`, destinado a distribuições baseadas em Debian e Ubuntu.

## Instalação do pacote DEB

No terminal, acesse a pasta onde o arquivo foi baixado e execute:

```bash
sudo apt install ./QAVault_<VERSAO>_amd64.deb
```

Substitua `<VERSAO>` pela versão baixada.

Exemplo:

```bash
sudo apt install ./QAVault_0.1.6_amd64.deb
```

## Abrir o aplicativo

Após a instalação:

- procure por **QA Vault** no menu de aplicativos; ou
- execute o aplicativo pelo atalho criado pelo pacote.

## Bandeja do sistema

Dependendo da distribuição e do ambiente gráfico, o ícone do QA Vault pode aparecer:

- diretamente na barra;
- na área de ícones ocultos;
- em uma extensão de indicadores do sistema.

## Captura de tela

A captura pode variar conforme o ambiente gráfico utilizado, especialmente entre X11 e Wayland.

Caso a captura não funcione:

1. confirme qual sessão gráfica está ativa;
2. verifique permissões de captura;
3. consulte os logs exibidos pelo aplicativo;
4. abra uma issue informando distribuição, versão e ambiente gráfico.

## Remoção

```bash
sudo apt remove qavault
```

O nome exato do pacote pode variar. Consulte:

```bash
dpkg -l | grep -i qavault
```

## Problemas

[Abra uma issue](https://github.com/gersoncdias/qavault-app/issues/new) informando a versão do QA Vault, sua distribuição Linux e o ambiente gráfico utilizado.
