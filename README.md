# Exercício Projeto Completo CRUD #

**Requisito:** a solução deverá ser feita em uma aplicação Web com Java.

**Diferenciais:** não é obrigatório fazer, porem caso siga as especificações abaixo será melhor avaliado. Caso não saiba todas pode aplicar somente as que você conhece.

- Separar a aplicação em frontend e backend utilizando REST
- Utilizar empacotamento WAR e EJB
- Utilizar JPA com Hibernate
- Utilizar Angular 5 ou 6

## Problema:

Um hospital precisa de um sistema que faça a ficha do cliente e valide se o plano do beneficiário é válido para o atendimento solicitado.

- A solução deverá implementar um CRUD, inserindo, pesquisando com filtros, alterando e deletando a ficha. 
- A ficha do paciente deverá conter o nome do paciente, número da carteira, Especialidade desejada e o Plano de saúde.
- Os planos de saúde e as especialidades estão nas respectivas tabelas no banco de dados (PlanosDeSaude e Especialidades). Ambos devem ser um combo na tela.
- Ao salvar a solução deverá validar a seguinte regra ao inserir ou alterar:
	- Um paciente pode cadastrar apenas uma ficha para o mesmo plano e especialidade.
	- Caso exista uma duplicidade para o mesmo plano e especialidade o sistema deve exibir uma mensagem: “Esta especialidade X já foi utiliza para o plano Y”.
	- Caso não exista duplicidade o sistema deve registrar as informações no banco de dados.

## Banco de dados:

Utilizar o banco de dados Microsoft SQL Server ou PostgresSQL para implementar o seguinte diagrama de entidade e relacionamentos:

![estagio](estagio.png)

## O que deve ser entregue?

- Código fonte.
- Script de criação da estrutura do banco. 




## O que eu fiz?

- Codigo de HTML5 E CSS3 "parte de frontend".
![image](https://user-images.githubusercontent.com/112522763/215114599-a3f0b31b-a0fe-42e1-b26c-67738ddc47a8.png)
