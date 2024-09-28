# Projeto LEDA1 passwords
Este projeto é focado na aplicação e análise de algoritmos de ordenação com base no arquivo "passwords_formated_data.csv". Entretanto, considerando que a execução completa do arquivo principal poderia ser muito demorada, um arquivo menor, chamado "passwords_formated_9k.csv", foi gerado com amostras aleatórias para permitir um retorno mais rápido durante os testes.

## Objetivo do projeto
Este projeto tem como objetivo explorar a execução de algoritmos de ordenação usando um Dataset contendo detalhes sobre as senhas mais utilizadas. Além da análise dos algoritmos, o projeto inclui formatações na base de dados, como a criação de uma coluna para classificar as senhas e a padronização das datas para o formato dd/mm/aaaa.

Embora o projeto trabalhe com o arquivo principal "passwords_formated_data.csv", devido ao longo tempo de processamento, um arquivo reduzido com 9.000 linhas foi criado para acelerar os testes e facilitar a comparação dos resultados em diferentes máquinas.


## Caso deseje utilizar o arquivo de dados completo, siga as instruções abaixo:
- Navegue até a pasta src
- Abra a Classe GetInput.java
- Encontre o método converteParaArray
- Modifique o parâmetro do arquivo para "dataset/passwords_formated_data.csv". Haverá comentários no código, sinalizando onde mudar o parâmetro.

## Requisitos
- JDK 17.0.12 e uma IDE da sua preferência (recomendamos o Intellij ou Eclipse)

## Instruções de Execução
- Use o comando git clone https://github.com/GustavoSouza07/ProjetoLeda_passwords1.git
- Execute a classe Main para iniciar o processo.

