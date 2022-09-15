Por padrão o privilégio para excutar scripts é o Restricted, ou seja, nenhum script chamado via arquivo pode ser executado apenas em modo interativo (via console ou ISE)

Para alterar a politica de execução use o cmdlet e algum dos seguinte
```
Set-ExecutionPolicy Unrestricted 
```
*Restricted*: É valor padrão (Windows 8, Windows Server 2012, and Windows 8.1) , não permite que nenhum arquivo seja executado isso inclui arquivos de configuração (.ps1xml), módulos (.psm1) e .ps1

*AllSigned*: Permite a execução de arquivos, porém necessita que os arquivos sejam assinados por um publicador confiável.

*Unrestricted*: Scripts não assinados podem rodar.

*Bypass*: Nada é bloqueado e não emite warnings ou prompts (pergunta se deseja executar algo por exemplo)

*Undefined*: Define a politica de execução indefinida. Se todos os escopos forem Undefined por padrão ela vira Restricted. Pode verificar os diferentes níveis com:

Get-ExecutionPolicy -list
Leitura recomendada:

Set-ExecutionPolicy

About Execution Policies
