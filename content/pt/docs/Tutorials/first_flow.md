---
title: "Primeiro Flow"
date: 2021-03-26
weight: 4
description: >
  Tutorial 1 - Construa seu primeiro flow
---

>   Este treinamento será baseado em um caso de uso, para este caso, está
>   disponível um vídeo para ser utilizado para treinamento da rede neural, que
>   terá o objetivo de detecção do elemento Porca, identificando suas faces
>   (face lisa e face prospecção)

## Caso Uso: Detecção e Identificação da Face das Porcas

### Objetivo:
Identificar a face das porcas, informando se a face é lisa ou se a face é prospecção

![Porca](/screenshots/ec5e47ae04a38e9fdf615ecc47ccb97d.png "Porca face lisa")
![Porca](/screenshots/5801a2ce81fee943c1a839d20dc38c53.png "Porca face prospecção")

## Siga os passos abaixo

###  Login – Entre na plataforma EyeFlow

Acesse:

```
https://app.eyeflow.ai
**Usuario**: treinamento
**Senha**: Teste
```
![](/screenshots/54452b239b80e31c2b115e38884a828f.png)

## Aplicação

Aplicação é um subdiretório, área disponibilizada na ferramenta, em que o
usuário pode criar seus projetos (aplicações) para executar na rede neural.

#### Click na Aba de Aplicação

![](/screenshots/278595a445b84611c12da54e179d4a85.png)


#### Crie uma nova aplicação, pressionando o botão \< + \>

![](/screenshots/8aa5d0c1d01eab46d7f83cfcf61a024e.png)


#### Crie uma Aplicação com nome \<SERPRO.nome do aluno\>

![](/screenshots/5aeb0464310d01fd998a3330b34ab08a.png)


## Flow

A solução permite ao usuário criar o fluxo para execução da rede neural.
Esta solução baseia-se em uma ferramenta Drag and Drop (Arrastar e Soltar)
de fácil manuseio onde os usuários podem utilizar os componentes dispostos
em seu Menu.

#### Click na Aba Fluxo

![](/screenshots/9624b3918209942bbedc3281fe844f9e.png)


Antes de Criar fluxo vamos conhecer os componentes existentes na Ferramenta, na imagem faremos uma breve descrição:

![](/screenshots/b9ee846a7bef5d5a7d875987ec191d01.png)
![](/screenshots/86ee8dc27659b8a3a46be6ca58af2a22.png)


![Câmera IP tipo Box - Planet Ello](/screenshots/ee5978b24eedb262e89aeb7872e05661.jpeg)
**Imagens dos modelos cameras informados:**

![](/screenshots/e47655b354ef9adf5ab04391acf39f75.png)
![Flea3 USB3 \| FLIR Systems](/screenshots/6fe5ed6c4580c42d994e0f89ab9e8daf.png)
![5MP Camera for NVIDIA Jetson Xavier NX / Nano developer kit](/screenshots/66934571ab2954b852cd3f5c3cc311ab.jpeg)
![](/screenshots/a1b0663d945545f97c22c6ccdc81b022.png)
![](/screenshots/26680cdce30aa9c375711fa8faa957e6.png)

##  Construa seu Flow

**Input**

#### CAMERA IP – Arraste o componente para o fluxo

![](/screenshots/bcaa17768ffda276bfd23eb259fc2126.png)


#### Double Click no componente CAMERA IP, aparecerá a tela abaixo:

![](/screenshots/cff838b4aeabb285995b06346a14e70e.png)


**Seletor**

#### ROI CUTTER – Arraste o componente para o Fluxo

![](/screenshots/21d08445d07222cf875416ca0b88be0a.png)


#### Double Click no componente ROI CUTTER, aparecerá a tela abaixo:

![](/screenshots/337b7304a836759447829c0218facd79.png)


**Siga os passos**

![](/screenshots/8f0d29dda6f9f27221d1e211c5dd27b8.png)


#### Crie uma nova Classe, seguindo passo representado abaixo:

![](/screenshots/b58b2a563154be20185941b41f43cf6d.png)


Aparecerá a imagem abaixo, nesta etapa estaremos adicionando duas novas classes

![](/screenshots/07fba474794f9334206980b7b17e212a.png)


#### Salve as configurações realizadas no componente ROI CUTTER

![](/screenshots/e6a94df39e040762c7292296b673e677.png)


#### Faça a comunicação entre a CÂMARA IP com ROI CUTTER no fluxo

![](/screenshots/55b2a4a94b260d0d95d41a746cf6320f.png)


#### Salve o Flow: Click no botão \<Save Flow\>

![](/screenshots/c6d71a06358b7b35cfa5d3ecf4340ea0.png)


##  Upload

Para este treinamento foi disponibilizado um vídeo teste:
Endereço do vídeo para Download
![Upload](/screenshots/13526a42e6cba74c2ca123581f41d23d.png)
![Flow](/screenshots/036889fd1c08813042e32d9fe50439a9.png)
![](/screenshots/8f54bde44fd3300b8923ce16c7d6bafc.png)

## Carregue o vídeo
#### Click no botão \<Teste Vídeo\>
![](/screenshots/4beaed025791a12acf13245f6156b0d7.png)


#### Faça o upload de Video teste, click no botão \<UPLOAD VIDEO\>

![](/screenshots/6ff411258db74b91e1ecacf0db27e66e.png)


#### Arraste o vídeo para o local informado

![](/screenshots/2d4a53d3b31d9783e49fc511c615004c.png)


Neste momento aparecerá uma barra demonstrando a carga do vídeo na ferramenta

![](/screenshots/626a6c42c6b044d26f05fd704fe91eac.png)


Neste momento a solução estará executando o seu fluxo criado e disponibilizando novos exemplos (frames) para seu Dataset.

## Dataset
![Dataset](/screenshots/e11aa076d81124afd80c34d4cdfe8d09.png)
![Upload](/screenshots/13526a42e6cba74c2ca123581f41d23d.png)
![Flow](/screenshots/036889fd1c08813042e32d9fe50439a9.png)

![](/screenshots/8f54bde44fd3300b8923ce16c7d6bafc.png)


#### Entre na Aba DATASETS

![](/screenshots/cb0d9f16e443fad19887ac227943415c.png)


Abrirá a pasta do Dataset

![](/screenshots/2c258bb34ea7d868a9c67fb6a019439d.png)


#### Selecione frames/imagens para ser treinadas no Dataset, click nos botões de seleção

![](/screenshots/911c7bcf7b17c08f3c2da836c62e6165.png)


#### Insira os novos exemplos selecionados, click no botão \<Insira novos exemplos\>

![](/screenshots/94702afc11390778519bb29e9439d074.png)


#### Retorne para a Aba Dataset

![](/screenshots/a3ac82b770d68bce6bb087659a597bce.png)


#### Click no seu Dataset criado

![](/screenshots/8f36879c60fbf6b59200f537e27f2605.png)


#### Marque as regiões de interesse, selecionando a Porca com a Face Lisa e com a Face Projeção

![](/screenshots/c55290311d8113c5c93a917cd5cef3e3.png)


Após a marcação de todos os frames selecionados click no botão \<Painel de Treino\>

![](/screenshots/18e3818244e9afbe876baf9392c69560.png)


## Edição de Parâmetros para treinamento da rede neural

### Siga os passos abaixo

![](/screenshots/16b5d277d6395f1288ab844a59fbc686.png)


Aparecerá a imagem abaixo

>  Descrição dos parâmetros na ferramenta
![](/screenshots/22c40d8d1c363711e6f5e3a39b924112.png)


## Treinamento da rede neural
![](/screenshots/8f54bde44fd3300b8923ce16c7d6bafc.png)
![Upload](/screenshots/13526a42e6cba74c2ca123581f41d23d.png)
![Flow](/screenshots/036889fd1c08813042e32d9fe50439a9.png)

![Dataset](/screenshots/e11aa076d81124afd80c34d4cdfe8d09.png)
![Training](/screenshots/3b897c90fad29c16aea0f2675bbe949b.png)

Após edição dos parâmetros da rede neural, vamos submeter os seus frames marcados para treinamento, onde executará o fluxo criado.

#### Siga os passos abaixo

![](/screenshots/ee2abb31954fea2099d8790c8dd0429d.png)


Aparecerá um pop-up na tela com o pedido de confirmação

![](/screenshots/646bc2a77c289b3e681f03f328ecae5a.png)


Após esta etapa, aparecerá uma tela com o andamento do treinamento

![](/screenshots/33e934dfaa47afa81bcff852189c6b34.png)


## Teste -resultado

Após o treinamento da rede neural, você poderá ver o resultado do
treinamento no relatório demonstrado na imagem, você também poderá
executar o vídeo carregado e observar o resultado que alcançou, caso o
resultado não seja satisfatório, a rede neural deverá realizar um novo
treinamento, para este caso, devemos submeter novos exemplos no Datasets,
com o objetivo de melhorar o aprendizado da rede neural

![](/screenshots/b3810a2f7f2f9724e96680b013bb77ed.png)


## Validação no vídeo

Conforme visto anteriormente no item Flow, a ferramenta disponibiliza a opção de teste no vídeo carregado.

### Siga os passos abaixo

#### Click na Aba \< Flow\>

![](/screenshots/ef0e2286e9d11d6f3a8292ad4bfb8c08.png)


#### Siga os passos abaixo

![](/screenshots/db80a153eac05e2394fdd281d30392ed.png)


#### Siga os passos abaixo

![](/screenshots/949318d213279ca64c1db3fe43563b42.png)


Após esta etapa você poderá verifica no vídeo o resultado do seu Projeto, se
o resultado não for satisfatório, a rede neural deverá ser submetida a um
novo treinamento, para isso você deverá executar os passos informados no
item Datasets, este processo deve ocorrer até a rede neural encontrar o
resultado satisfatório.
