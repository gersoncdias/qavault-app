# Política de Segurança

A segurança das evidências e dos dados dos usuários é uma prioridade para o QA Vault.

## Versões suportadas

A versão mais recente publicada é a versão que recebe correções de segurança e manutenção.

| Versão | Suporte |
|---|---|
| Versão mais recente | ✅ |
| Versões anteriores | ⚠️ Avaliado caso a caso |

Recomendamos manter o aplicativo sempre atualizado.

## Como reportar uma vulnerabilidade

Não publique vulnerabilidades, credenciais, tokens ou dados sensíveis em uma issue pública.

Para reportar uma possível vulnerabilidade:

1. Acesse a aba **Security** deste repositório.
2. Utilize **Report a vulnerability** para abrir um GitHub Private Security Advisory.
3. Inclua uma descrição objetiva do problema.
4. Informe a versão afetada.
5. Adicione passos de reprodução seguros.
6. Explique o possível impacto.
7. Não inclua evidências reais ou dados de terceiros.

Caso a opção de relatório privado ainda não esteja habilitada, utilize o canal de contato disponível em:

https://qavault.com.br

## O que incluir no relatório

- Versão do QA Vault
- Sistema operacional
- Componente afetado
- Passos para reprodução
- Resultado esperado
- Resultado observado
- Impacto potencial
- Sugestão de correção, quando houver

## Escopo de segurança

Exemplos de problemas que devem ser comunicados de forma privada:

- acesso não autorizado a evidências;
- falhas de autenticação ou autorização;
- exposição de tokens ou dados pessoais;
- manipulação de links compartilhados;
- upload de arquivos maliciosos;
- path traversal;
- execução remota de código;
- falhas relacionadas a integrações de armazenamento;
- exposição de informações internas da infraestrutura.

## Boas práticas para usuários

- Não compartilhe links de evidências em canais públicos sem necessidade.
- Revise a evidência antes de gerar ou copiar o link.
- Utilize a pixelização para ocultar dados sensíveis.
- Não envie senhas, tokens, documentos pessoais ou dados de produção.
- Mantenha o sistema operacional e o QA Vault atualizados.
- Revogue acessos de armazenamento que não sejam mais utilizados.

## Divulgação responsável

Pedimos que a vulnerabilidade não seja divulgada publicamente antes da análise e da disponibilização de uma correção.

A confirmação do problema, priorização e comunicação da solução serão realizadas de acordo com a gravidade e o impacto identificado.
