> # Exercício 05: Veículos usados 
> 
> Queremos desenvolver um sistema informático para uma concessionária de veículos usados. Essa concessionária decidiu que venderá apenas carros. Todos os carros têm marca, modelo, ano de fabricação, cor e quilometragem. 
> 
> Como estratégia de marketing, a concessionária quer ter um registro dos clientes que compram os veículos. O departamento de marketing da concessionária precisa saber o nome, o sobrenome e alguma informação de contato dos clientes para poder oferecer outros carros no futuro.
> 
> Por outro lado, o departamento de contabilidade da concessionária quer ter um registro das vendas realizadas. 
> 
> Cada registro deve ter as seguintes informações:
>   * valorDaVenda 
>   * veiculoVendido 
>   * cliente 
> 
> 1. Fazer um diagrama de classe representando o modelo que queremos implementar. 
> 
> 2. Implementar cada classe e definir os atributos. As classes que devem ser implementadas são: 
>     * Concessionária
>     * Cliente
>     * Venda
>     * Veículo
> 
> 3. Criar os construtores para as classes Cliente, Veículo e Venda. 
>     * Cliente terá como parâmetros:
>         * nome
>         * sobrenome
>         * contato
>     * Veículo terá como parâmetros:
>         * marca
>         * modelo
>         * ano de fabricação
>         * cor
>         * quilometragem
>     * Venda terá como parâmetros:
>         * cliente
>         * veículo
>         * valor da venda
> 
> 4. Definir, na classe Concessionária, o método registrarVenda(Veículo veículo, Cliente cliente, Double valor), que adiciona ao registro de vendas da concessionária uma nova venda de um veículo a um cliente por um valor determinado. 
> 
> 5. Definir uma nova classe chamada Exercicio5 e criar um método main.
> 
>     Dentro do método main, criar um carro, criar um cliente e registrar a venda desse veículo a esse cliente pela Concessionária.
