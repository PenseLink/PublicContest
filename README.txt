
Especificação da arquitetura da aplicação

Módulos 
	- Cadastro de Escola
	- Alocação de candidatos
	- Geração de folheterias
	
Aplicação dividida em camadas
	- Serviço
		- Interface -> Responsável por expor o contrato do serviço (request e response) utilizando DTO(Data Transfer Object) para uma assinatura mais enxuta
		- Validação -> Evitar o processamento de dados inválidos
		- Service -> Execução/Validação das regras de negócio
		- DAO -> Camada responsável pelo acesso aos dados
		- Entidades -> Definição da modelagem
		- RESTFULL ou SOAP ?
			- RESTFULL -> transferencia de dados através de JSON
			- SOAP -> Transferencia de dados através de XML
			
	- Apresentação
		- A definir, utilizar .jsp ou criar front utilizando um server NODEJS e Angular ?
		
