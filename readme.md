<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [⏱ Duração do treino](#-duração-do-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 2 dias              | Treino AB                   |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 4 dias              | Treino ABCD                 |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **AB**: Divisão do treino em dois dias: um para os músculos frontais, outro para os dorsais.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes (*push*-*pull*-*legs*).
- **ABCD**: Divisão do treino em quatro dias, com foco mais específico em grupos musculares complementares.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## ⏱ Duração do treino

A terceira regra é determinar quanto tempo o usuário quer que seu treino dure. Dependendo do tempo, a quantidade (e eventualmente o tipo) de exercícios varia:

|**Imagem**                                                         | **Duração**    | **Descrição**                                                            |
| ----------------------------------------------------------------- | -------------- | ------------------------------------------------------------------------ |
| <img src=".github/assets/30minutos.png" width="75" height="75"> | **30 minutos** | Um a dois exercícios por grupo muscular, cada um com três séries.        |
| <img src=".github/assets/45minutos.png" width="75" height="75"> | **45 minutos** | Dois a três exercícios por grupo muscular, cada um com três séries.      |
| <img src=".github/assets/60minutos.png" width="75" height="75"> | **60 minutos** | Três exercícios por grupo muscular, cada um com quatro séries.           |
| <img src=".github/assets/75minutos.png" width="75" height="75"> | **75 minutos** | Idem 60 minutos, com acréscimo de 15 minutos de outro tipo de exercício. |

---

## 🏋️ Tipos de Exercícios

A quarta regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                     | **Tipo de Treino** | **Descrição**                                                                     |
| -------------------------------------------------------------- | ------------------ | --------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="75" height="75"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.    |
| <img src=".github/assets/4760665.png" width="75" height="75">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.              |
| <img src=".github/assets/barr.png" width="75" height="75">     | **Peso Livre**     | Exercícios com pesos livres, que trabalham vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="75" height="75">   | **Cardio**         | Exercícios para resistência cardiovascular, como corrida ou ciclismo.             |
| <img src=".github/assets/hiit.png" width="75" height="75">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.          |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Determine qual deve ser a duração do treino**, e escolha o tempo mais adequado.
4. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
5. **Use o prompt do assistente** para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
