Builds automatizados permitem a construção e atualização de imagens automaticamente, no Docker Hub, por meio de um repositório GitHub ou Bitbucket contendo um Dockerfile.
****
Para configurar uma compilação automatizada.
-----------
 - Crie uma conta Docker Hub.
 - Vincular sua conta do GitHub ou Bitbucket através do menu "Vincular contas".
	- Para adicionar, remover ou visualizar sua conta vinculada, vá para a seção do seu perfil Hub "Settings" "Linked Accounts & Services".
 - Selecione "Create Automated Build” no menu Create.
 - Escolha um projeto GitHub ou Bitbucket que tem um Dockerfile que você quer construir.
 - Escolher o branch que você quer construir (o padrão é o master branch).
 - Dê um nome ao Automated Build.
 - Atribuir uma tag Docker opcional para o Build.
 - Especificar onde o Dockerfile está localizado. O padrão é /.
 - Ativar GitHub service hooks no GitHub.