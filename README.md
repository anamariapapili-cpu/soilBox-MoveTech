#  SoilBox

### Análise de solo de forma portátil, simples e prática.

O **SoilBox** é um projeto desenvolvido pela equipe **MoveTech** para ajudar na análise das condições do solo.

A ideia surgiu a partir de uma pergunta simples:

> **Como podemos entender melhor o solo antes de pensar em recuperar uma área degradada?**

Foi daí que começamos a desenvolver uma maleta portátil capaz de reunir sensores, programação e impressão 3D em uma única solução.

---

##  O projeto

O SoilBox realiza leituras diretamente no solo e apresenta os resultados no próprio equipamento.

O usuário posiciona a maleta no local que deseja analisar, insere os sensores no solo e inicia a leitura.

A **ESP32** recebe os dados dos sensores, processa as informações e mostra os resultados no display.

---

##  O que analisamos

O sistema foi desenvolvido para trabalhar com dados como:

* pH
* umidade
* temperatura
* condutividade elétrica
* nitrogênio
* fósforo
* potássio

Essas informações ajudam a entender melhor as condições encontradas em cada ponto analisado.

---

##  Como funciona

```text
Solo
  ↓
Sensores
  ↓
ESP32
  ↓
Processamento
  ↓
Resultado no display
```

A proposta é que o SoilBox possa ser levado até diferentes pontos de uma área, permitindo fazer análises diretamente no local.

---

##  O que usamos

**Eletrônica**

* ESP32
* sensores de solo
* display
* componentes eletrônicos

**Programação**

* C++
* PlatformIO
* Arduino Framework

**Construção**

* modelagem 3D
* impressão 3D
* prototipagem
* testes

---

##  Neste repositório

Aqui estamos compartilhando parte do desenvolvimento do SoilBox.

Você encontrará:

```text
SoilBox/
│
├── code/
│   └── programação
│
├── 3D/
│   └── arquivos para impressão
│
├── images/
│   └── fotos do projeto
│
└── README.md
```

###  Arquivos 3D

Disponibilizamos os modelos utilizados na construção do projeto para que outras pessoas possam estudar, imprimir, adaptar e criar novas versões.

###  Código

Também compartilhamos a programação utilizada no SoilBox.

Assim, outras equipes e estudantes podem entender como o sistema funciona e usar nosso projeto como ponto de partida para novos testes e melhorias.

---

##  Nosso processo

O projeto passou por várias mudanças até chegar à versão atual.

Não queríamos apenas colocar sensores dentro de uma caixa.

Testamos o posicionamento dos componentes, a organização interna, a estrutura da maleta e a programação até encontrar uma solução que fosse mais prática para o uso em campo.

```text
Pesquisa → Ideia → Protótipo → Testes → Melhorias
```

E o projeto continua evoluindo.

---

##  Por que o SoilBox?

Porque antes de pensar em recuperar uma área, precisamos entender o que está acontecendo nela.

O SoilBox foi criado justamente para aproximar **tecnologia e meio ambiente**, utilizando dados para conhecer melhor as condições do solo.

---


##  MoveTech

Somos a **MoveTech**.

Gostamos de pesquisar, construir, testar, errar, melhorar e transformar ideias em projetos reais.

O SoilBox representa um pouco desse processo.

**Tecnologia para entender o ambiente e criar novas possibilidades. 🌱**
