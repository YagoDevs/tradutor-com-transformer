# Aluno: Yago Phellipe Matos Lopes
## Curso: Ciência da Computação

## Ponderada - Tradutor com Transformer

### Pontos Positivos e Negativos

#### **Pontos Positivos:**
- O código é didático e proporciona um entendimento profundo da arquitetura Transformer, podendo verificar como é construido o decoder e encoder.
- A utilização do `tensorflow_datasets` facilita o carregamento e a manipulação do conjunto de dados.
- A abordagem com o `Keras` proporciona uma implementação mais organizada com `Model` e `Layer`.

#### **Pontos Negativos:**
- **Desatualizações:** O código estava muito desatualizado, e precisei atualizar várias bibliotecas (`tensorflow`, `tensorflow-text` e `tensorflow-datasets`), o que dificultou a implementação.
- **Complexidade:** A implementação manual do `Encoder` e `Decoder` tornou o código extenso. Seria mais simples utilizar o `tf.keras.layers.Transformer`.
- **Tempo de Execução:** Sem GPU, a execução é extremamente lenta. Apenas 1 época levou muito tempo.
- **Alto Consumo de Memória:** A carga de dados e o treinamento consomem muitos recursos de hardware.

---
