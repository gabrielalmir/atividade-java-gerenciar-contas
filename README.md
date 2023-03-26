# Projeto Gerenciador Simples de Contas Bancárias em Java

Este é um projeto simples de uma Conta Bancária em Java. A classe Conta possui um construtor que recebe como parâmetros o nome do titular da conta, o nome do banco, a agência e o saldo inicial. A partir desses dados, é gerado um ID para a conta por meio da classe UUID.

Em um projeto real não é indicado utilizar substring para gerar o ID da conta, pois há a possibilidade de gerar IDs repetidos. Para evitar isso, é necessário utilizar um banco de dados para armazenar os IDs gerados e verificar se o ID gerado já existe no banco de dados. Caso exista, um novo ID deve ser gerado.

A classe Conta possui métodos para depositar e sacar valores da conta, além de getters e setters para cada um dos atributos. Além disso, a classe sobrescreve o método toString para exibir os dados da conta formatados.

O objetivo deste projeto é fornecer uma base simples para a implementação de uma conta bancária em Java. Ele pode ser facilmente estendido com novos métodos e atributos, de acordo com as necessidades específicas de cada projeto.

Para executar o projeto, é necessário ter uma instalação do Java e um ambiente de desenvolvimento configurados. O projeto pode ser executado a partir de um IDE, como o Eclipse ou o IntelliJ, ou a partir da linha de comando usando o compilador javac e o executável java.

## Atividades

Atividade lecionada pelo professor [Marcos Roberto de Moraes](https://github.com/maromo71)

- [x] Criar um repositório no GitHub para o projeto
- [x] Criar um projeto Java no IntelliJ
- [x] Criar a classe Conta
- [x] Criar o método construtor da classe Conta
- [x] Criar os métodos depositar e sacar
- [x] Criar os getters e setters
- [x] Criar o método toString
- [x] Criar menu de opções
- [x] Switch case para as opções do menu
- [x] Criar um ArrayList de contas
- [x] Criar um método para criar uma nova conta
- [x] Criar um método para sacar de uma conta
- [x] Criar um método para depositar em uma conta
- [x] Criar um método para exibir os dados de uma conta
- [x] Criar um método para mostrar o patrimônio total das contas

### Autor

Este projeto foi desenvolvido por  [Gabriel Almir](https://github.com/momentoalmir).

### Licença

Este projeto está licenciado sob a licença MIT. 

Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.