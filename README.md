Este projeto é uma calculadora simples que utiliza os conceitos de herança e polimorfismo em C++. 
O código permite realizar operações aritméticas básicas (adição, subtração, multiplicação e divisão) 
sem o uso de condicionais repetitivas, aplicando o Princípio da Substituição de Liskov. 
Cada operação é representada por uma classe derivada que implementa a interface de uma classe abstrata.

Funcionalidades

	•	Operações disponíveis: +, -, *, /
	•	Implementação de herança para organizar as operações em classes especializadas
	•	Polimorfismo para invocar operações de forma flexível
	•	Utilização de std::shared_ptr para gerenciamento de memória automático

Conceitos Implementados

	•	Classe abstrata Operacao: Define o método calcular() de forma abstrata para ser implementado pelas subclasses.
	•	Subclasses: Soma, Subtracao, Multiplicacao, e Divisao, cada uma implementa o método calcular() conforme a operação aritmética.
	•	Polimorfismo: A operação é escolhida em tempo de execução com base no operador fornecido pelo usuário.
	•	Liskov Substitution Principle (LSP): As subclasses podem substituir a classe base sem alterar a funcionalidade do programa.
