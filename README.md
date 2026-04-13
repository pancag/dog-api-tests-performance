# Teste de Carga e Pico - Aplicação Web

Este projeto realiza testes de carga e pico em uma aplicação web, utilizando o Apache JMeter. O objetivo é avaliar a performance da aplicação sob diferentes níveis de carga e garantir que os requisitos de desempenho sejam atendidos.

## Índice

1. [Descrição do Projeto](#descrição-do-projeto)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Instruções para Execução](#instruções-para-execução)
4. [Relatório de Execução dos Testes](#relatório-de-execução-dos-testes)
5. [Conclusão](#conclusão)
6. [Contribuição](#contribuição)
7. [Licença](#licença)

## Descrição do Projeto

Este projeto realiza testes de carga e pico em uma aplicação web, utilizando o Apache JMeter. O objetivo é avaliar a performance da aplicação sob diferentes níveis de carga e garantir que os requisitos de desempenho sejam atendidos.

## Tecnologias Utilizadas

- Apache JMeter
- Java (se necessário)
- Git

## Instruções para Execução

1. **Clone o Repositório:**

2. **Abra o Apache JMeter:**
- Certifique-se de ter o Apache JMeter instalado.

3. **Carregue o Plano de Teste:**
- Abra o arquivo .jmx que está no diretório do projeto.

4. **Execute os Testes:**
- Clique no botão de "play" para iniciar os testes.
- para linha de comando:
- ```jmeter -n -t ./test_plan/seu_test.jmx -l results.jtl -j jmeter.log```

5. **Analise os Resultados:**
- Verifique os resultados no Listener "Summary Report" e results.jtl.
