#  Projeto AR - Visualização de Carros em Realidade Aumentada

##  Descrição

Este projeto tem como objetivo demonstrar a visualização de modelos 3D de carros utilizando **Realidade Aumentada (AR)** diretamente no navegador.

O usuário pode acessar o sistema através de um QR Code ou link e, ao apontar a câmera para marcadores impressos, visualizar diferentes veículos em 3D, podendo ainda alterar suas cores em tempo real.

---

##  Funcionalidades

* 📱 Acesso via QR Code
*  Detecção de marcadores (A, B, C, D)
*  Visualização de 4 carros diferentes:

  * BMW Série 3
  * BMW X5
  * Fiat Palio
  * Fiat Uno
*  Troca de cores interativa
*  Controles de:

  * Escala
  * Posição
  * Rotação

---

##  Tecnologias Utilizadas

* HTML5
* JavaScript
* A-Frame
* AR.js

---

##  Estrutura do Projeto

```
projeto-carros-ar
├── index.html
├── bmw3_preto.glb
├── bmw3_prata.glb
├── bmw3_vermelho.glb
├── x5_preto.glb
├── x5_prata.glb
├── x5_branco.glb
├── palio_preto.glb
├── palio_prata.glb
├── palio_vermelho.glb
├── uno_preto.glb
├── uno_prata.glb
├── uno_branco.glb
├── pattern-letterA.patt
├── pattern-letterB.patt
├── pattern-letterC.patt
├── pattern-letterD.patt
```

---

##  Como Executar

###  Localmente

1. Abra o terminal na pasta do projeto
2. Execute:

```
node server.js
```

3. Acesse:

```
http://localhost:3000
```

---

### 🔹 Online (GitHub Pages)

Acesse o projeto diretamente pelo link:

```
https://judgepinheiro.github.io/projeto-carros-ar/
```

---

##  Como Utilizar

1. Escaneie o QR Code do projeto
2. Permita o acesso à câmera
3. Aponte para um dos marcadores impressos
4. Interaja com o modelo 3D

---

##  Marcadores

Utilize os seguintes marcadores impressos:

* 🅰 BMW Série 3
* 🅱 BMW X5
* 🅲 Fiat Palio
* 🅳 Fiat Uno

---

##  Observações

* É necessário utilizar um dispositivo com câmera (preferencialmente celular)
* O projeto funciona melhor em navegadores modernos (Chrome recomendado)
* É necessário conexão HTTPS para funcionamento da câmera

---

##  Autor

Mateus Pinheiro

---

##  Licença

Este projeto foi desenvolvido para fins acadêmicos.
