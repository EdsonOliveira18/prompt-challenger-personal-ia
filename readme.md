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
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino e Alimentação Ideais</h3>
Este projeto é um desafio de Prompt Engineering, onde o objetivo é criar um prompt que ajude a montar o treino e o plano alimentar ideais para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo, tipo de exercícios preferidos e objetivos nutricionais. O assistente será capaz de personalizar tanto os treinos quanto a alimentação com base nas características e necessidades do usuário, otimizando os resultados.
</p>

## 📋 Índice

1. 📝 Introdução  
2. 💪 Biotipos Corporais  
3. 📅 Dias Disponíveis para Treino  
4. 🏋️ Tipos de Exercícios  
5. 🥗 Alimentação Adequada  
6. 🛠️ Regras de Negócio  
7. 📖 Material de Apoio  
8. 🎯 Prompt de Resposta Propost

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que não só gera treinos personalizados, mas também oferece orientações alimentares alinhadas aos objetivos do usuário, como ganho de massa muscular, perda de peso ou manutenção. O usuário fornecerá informações como biotipo corporal, dias disponíveis para treino, tipo de exercício preferido e suas metas alimentares. Com essas informações, o assistente gerará um plano de treino e sugestões alimentares personalizadas.

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
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🥗 Alimentação Adequada  
A quarta regra adicionada ao assistente é sugerir uma alimentação que otimize os resultados do treino. A dieta será ajustada de acordo com o biotipo, o número de treinos semanais e o tipo de exercícios:

| **Objetivo**           | **Sugestão de Alimentação** |
| ---------------------- | -------------------------- |
| Ganho de Massa Muscular | Dieta hipercalórica, com ênfase em proteínas (frango, carne vermelha magra, ovos), carboidratos complexos (arroz integral, batata-doce) e gorduras saudáveis (abacate, castanhas). |
| Perda de Peso          | Dieta hipocalórica, focada em proteínas magras (peixes, tofu), vegetais ricos em fibras e controle de carboidratos (cortar açúcares refinados). |
| Manutenção             | Dieta balanceada, com proporções equilibradas de carboidratos, proteínas e gorduras saudáveis, mantendo a ingestão de calorias moderada. |

---

## 🛠️ Regras de negócio

- Identifique seu biotipo corporal consultando a seção de biotipos.
- Determine quantos dias por semana você pode treinar e escolha o tipo de treino mais adequado.
- Selecione o tipo de exercício que prefere realizar e que se encaixa melhor nos seus objetivos.
- Use o prompt do assistente para gerar um plano de treino personalizado com orientações alimentares adequadas.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto
Aqui, o prompt será configurado para coletar as informações do usuário e gerar um plano de treino e alimentação personalizados:

**Exemplo de Prompt:**  
"Com base no seu biotipo corporal [inserir], quantos dias por semana você pode treinar [inserir], e o tipo de exercício que você prefere [inserir], o sistema irá sugerir um treino personalizado e um plano alimentar que maximiza seus resultados."

