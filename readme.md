# App para salvar documentos na nuvem

- Precisamos que o usuario consiga enviar um documento de diferentes tipos: pdf ou imagem. A partir disso nosso backend deve
poder enviar esse documento para a nuvem e mostrar que ele esta ali e que pode ser salvo


## RFs
[] Deve ser possivel criar um novo documento
[] Um usuario deve poder ver todos os documentos criados
[] Deve ser possivel baixar um documento
[] Deve ser possivel excluir um documento
[] Deve ser possivel buscar as caracteristicas de um usuario pelo OAuth

## RNs
[] Os usuarios só podem ver seus proprios documentos

- Documento
ID
Nome
cloud key
categoria 
data de criação

- Usuario
ID
Nome
Sobrenome
Idade
metricas
Email
Avatar Url

auth com google