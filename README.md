# Projeto BRACIS

Este repositório contém os módulos desenvolvidos para previsão de consumo de energia e para controle de um medidor IoT embarcado em um ESP32.

## 📁 Pasta `previsao`

Contém os arquivos relacionados ao módulo de previsão de consumo:

- `codigo_pso.ipynb`: Notebook com a implementação do algoritmo PSO (Particle Swarm Optimization) para otimização dos hiperparâmetros da rede LSTM.
- `Ensemble_teste.ipynb`: Implementação completa do módulo de previsão com o modelo em ensemble.
- `testes_de_correlacao.ipynb`: Notebook utilizado para avaliar a correlação entre os dados de energia e o nível da barragem.
- `config_pso`: Arquivo com os valores obtidos dos hiperparâmetros otimizados via PSO.

## 📁 Pasta `medidor`

Contém os arquivos relacionados ao firmware embarcado no ESP32:

- `main/blink_example_main (medidor + webserver)`: Implementação do firmware do medidor IoT com suporte a webserver.
- `main/blink_example_main (emulação perfil Duas Unas)`: Código de emulação do perfil de consumo da EEAB Duas Unas.

---

Este repositório foi desenvolvido como parte do projeto submetido ao BRACIS.
