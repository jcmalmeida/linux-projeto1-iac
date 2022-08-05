**Projeto DIO - Infraestrutura como código: Script de criação de estrutura de usuários, diretórios e permissões**

Este é um projeto criado durante o bootcamp de Linux oferecido pela DIO. Foram definidos os seguintes requisitos:
- Criação de um arquivo do tipo *Bash Script*;
- O dono de todos os diretórios criados será o usuário `root`;
- Todos os usuários terão permissão total dentro do diretório `publico`;
- Os usuários de cada grupo terão permissão total dentro de seu respectivo diretório;
- Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem.

Diretórios:
- `/publico` (todos tem total permissão)
- `/adm` (`root` e `GRP_ADM` têm permissão)
- `/ven` (`root` e `GRP_VEN` têm permissão)
- `/sec` (`root` e `GRP_SEC` têm permissão)

Grupos:
- `GRP_ADM`
- `GRP_VEN`
- `GRP_SEC`

Usuários:
- Do `GRP_ADM`: `carlos`, `maria`, `joao`
- Do `GRP_VEN`: `debora`, `sebastiana`, `roberto`
- Do `GRP_SEC`: `josefina`, `amanda`, `rogerio`