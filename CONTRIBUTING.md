## Como contribuir?

* Se você for um colaborador externo, dê um fork no projeto
* Issues só poderão ser criadas com os templates especificados no repositório
* A criação de branches deve seguir a política de branches
* No desenvolvimento usar nossa política de commits

## Política de branches

Nossa política segue algumas características do Gitflow. Então separamos nossas branches em:

### *master*

A master será nossa branch de produção, ou seja, nela estará a versão estável do projeto. E por questões de segurança ela será bloqueada para commits e push. A interação com a master vai se dá através da de Pull requests que virão da branch **devel**.

### *devel*

A devel será nossa branch de desenvolvimento, ou seja, vai agrupar o trabalho vindo das branches de features, o objetivo é criar uma release que será submetida para **master**. 

### *branches de features*

As branches de features são criadas a partir da **devel**, e serve para o desenvolvimento de features presentes nas issues do repositório. No final do desenvolvimento a funcionalidade desenvolvida nessa branch deve ser enviada para a **devel**, através de um pull request.

Nomenclatura das branches de features:
	O nome das branches de features devem seguir um padrão `X_Nome_da_issue` , onde X é o número da issue correspondente a funcionalidade. 

### *hotfix branches* 

Hotfix branches são criadas a partir da **master** e servem para resolver de forma rápida os bugs em produção. Essa branch deve seguir a seguinte nomenclatura: hotfix_Nome_do_bug.
