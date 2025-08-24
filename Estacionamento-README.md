# Sistema de Estacionamento

Este é um sistema simples de **estacionamento** implementado em **C#**, que permite cadastrar, remover e listar veículos estacionados, além de calcular o valor a ser pago pelo tempo de permanência no estacionamento. O preço é calculado com base em um valor inicial e uma tarifa por hora, fornecida pelo usuário.

## Funcionalidades

O sistema possui um menu interativo com as seguintes opções:

1. **Cadastrar veículo**: Permite cadastrar a placa de um veículo no estacionamento.
2. **Remover veículo**: Remove um veículo do estacionamento, calculando o valor a ser pago com base no tempo que o veículo permaneceu estacionado.
3. **Listar veículos**: Exibe as placas dos veículos atualmente estacionados.
4. **Encerrar**: Finaliza o programa.

## Como utilizar

1. Ao iniciar o programa, você será solicitado a informar o **preço inicial** (valor fixo para cada veículo) e o **preço por hora** (valor a ser cobrado por hora de estacionamento).
2. O programa exibe um menu interativo onde você pode escolher uma das opções listadas acima.
3. A cada ação, o programa exibirá mensagens de confirmação ou erro, dependendo da sua escolha.

### Exemplo de Execução:

```plaintext
Seja bem vindo ao sistema de estacionamento!
Digite o preço inicial:
10
Agora digite o preço por hora:
5
Digite a sua opção:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar
```
## Cadastro de Veículo

Ao escolher a opção para cadastrar um veículo, o programa pedirá para inserir a placa do veículo. A placa será então adicionada à lista de veículos estacionados.

## Remoção de Veículo

Ao escolher a opção para remover um veículo, o programa pedirá a placa do veículo a ser removido. Se o veículo estiver estacionado, o sistema solicitará o tempo de permanência em horas e calculará o valor total a ser pago. Caso o veículo não seja encontrado, uma mensagem de erro será exibida.

## Listagem de Veículos

Escolhendo a opção para listar veículos, o sistema exibirá todas as placas dos veículos estacionados no momento.

## Encerramento

Ao escolher a opção para encerrar, o programa será fechado.

## Tecnologias

- C# (C Sharp)
- .NET 6.0 (framework para desenvolvimento)
