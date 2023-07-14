# Sistema de Países
Este projeto é um script em Python que se comunica com a API REST Countries para buscar informações sobre países. Ele é capaz de:

-Contar o número total de países;
-Listar todos os países;
-Mostrar a população de um país específico;
-Mostrar as moedas de um país específico;


## Dependências
Este projeto requer Python 3 e a biblioteca requests.

## Instalação
Para usar este script, primeiro instale a biblioteca requests do Python. Você pode fazer isso com o pip:

```bash
pip install requests
```


## Uso
Para usar o script, você deve fornecer ao menos um argumento na linha de comando. Aqui estão os argumentos possíveis:

`contagem`: retorna o número total de países;

`moeda <nome do país>`: retorna as moedas do país informado;

`populacao <nome do país>`: retorna a população do país informado.


Por exemplo, para obter as moedas do Brasil, você executaria o seguinte comando:

```bash
python paises.py moeda Brasil
```
