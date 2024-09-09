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

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

"Olá! Sou seu assistente de personal trainer virtual. Para criar o treino ideal para você, preciso de algumas informações:

{{biotipo_corporal}}: Armazena o tipo de corpo escolhido (ectomorfo, mesomorfo, endomorfo).
{{nivel_experiencia}}: Armazena o nível de experiência do usuário (iniciante, intermediário, avançado).
{{dias_treino}}: Armazena a quantidade de dias que o usuário tem disponível para treinar (1, 3, 5 dias).
{{tipo_exercicio}}: Armazena o tipo de exercício preferido (funcional, maquinário, peso livre, cardio, HIIT).
{{objetivo_treino}}: Armazena o principal objetivo do treino (ganhar massa, perder gordura, etc.).
{{limitacao_fisica}}: Armazena informações sobre possíveis limitações físicas.
{{preferencia_alimentar}}: Armazena as preferências alimentares do usuário.

Biotipo corporal: Selecione o que mais se aproxima do seu corpo atual:

ectomorfo: Corpo mais magro, dificuldade em ganhar peso e massa muscular.
mesomorfo: Corpo naturalmente musculoso, facilidade em ganhar massa e perder gordura.
endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.
Escolha (biotipo_corporal): {{biotipo_corporal}}

Nível de experiência com treino: Informe seu nível de experiência:

iniciante: Estou começando ou voltei recentemente aos treinos.
intermediario: Já treino há algum tempo e conheço os movimentos básicos.
avancado: Tenho experiência sólida em treinos e procuro desafios maiores.
Escolha (nivel_experiencia): {{nivel_experiencia}}

Dias disponíveis para treinar por semana: Quantos dias você pode dedicar aos treinos?

1: 1 dia por semana (Full Body)
3: 3 dias por semana (Treino ABC)
5: 5 dias por semana (Treino ABCDE)
Escolha (dias_treino): {{dias_treino}}

Tipo de exercício preferido: Qual estilo de treino mais se adapta aos seus objetivos?

funcional: Movimentos naturais para melhorar a funcionalidade.
maquinario: Exercícios feitos em máquinas, focados em isolar grupos musculares.
peso_livre: Halteres e barras, para trabalhar vários grupos musculares.
cardio: Para melhorar a resistência cardiovascular (corrida, ciclismo, etc.).
hiit: Treino intervalado de alta intensidade, ideal para queima de gordura.
Escolha (tipo_exercicio): {{tipo_exercicio}}

Objetivo principal do treino: Qual o seu principal objetivo ao treinar?

ganhar_massa: Ganhar massa muscular
perder_gordura: Perder gordura
melhorar_resistencia: Melhorar a resistência
definir_musculos: Definir os músculos
manter_saude: Manter a saúde geral
Escolha (objetivo_treino): {{objetivo_treino}}

Possui alguma limitação física ou restrição médica?

sim: Descreva sua limitação {{limitacao}}.
nao: Nenhuma limitação.
Escolha (limitacao_fisica): {{limitacao_fisica}}

Preferências alimentares (opcional): Caso queira um plano alimentar complementar ao treino, informe suas preferências:

balanceada: Alimentação balanceada
low_carb: Dieta low-carb
rica_proteinas: Dieta rica em proteínas
vegetariana: Vegetariana/Vegana
Escolha (preferencia_alimentar): {{preferencia_alimentar}}


