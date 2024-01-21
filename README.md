# Monitoramento de Sites

Este é um simples programa em Go para monitorar a disponibilidade de sites e registrar logs de seus status. O programa realiza verificações periódicas em uma lista de sites, exibindo o status de cada um e registrando os resultados em um arquivo de log.

## Funcionalidades

- **Iniciar Monitoramento:** Inicia o monitoramento dos sites listados em "sites.txt", exibindo o status de cada site.
- **Exibir Logs:** Exibe o conteúdo do arquivo de log, que registra as informações sobre a disponibilidade dos sites.
- **Sair do Programa:** Encerra a execução do programa.

## Como Usar

1. Clone este repositório ou baixe o código-fonte.
2. Certifique-se de ter um arquivo "sites.txt" contendo a lista de sites que deseja monitorar, um por linha.
3. Execute o programa e escolha uma opção do menu.

```bash
go run main.go
````


## Configurações

- **Número de Monitoramentos:** Definido pela constante monitoramentos, determina quantas vezes o programa irá verificar os sites..
- **Intervalo de Verificação:** Definido pela constante delay, determina o intervalo em segundos entre cada verificação.


## Exemplo de sites.txt

```bash
https://www.exemplo1.com
https://www.exemplo2.com
https://www.exemplo3.com
````

## Logs
Os resultados das verificações são registrados no arquivo "log.txt" no formato:

```bash
DD/MM/AAAA HH:mm:ss - Site - Online: true/false
````
