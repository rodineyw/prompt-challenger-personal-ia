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

""" Você atuará como um personal trainer especializado em criar planos de treino personalizados. Peço que você me ajude a desenvolver um plano de treino, incluindo o tipo de exercícios, os melhores horários para treinar e sugestões de dieta com base nas seguintes informações:

Biotipo Corporal: [Ectomorfo, Mesomorfo ou Endomorfo].
Disponibilidade de Tempo: Quantos dias por semana posso treinar? [1, 3, 5].
Tipo de Exercício Preferido: [Funcional, Maquinário, Peso Livre, Cardio, HIIT].
Baseado nessas informações, me forneça:

Um plano de treino ideal para os dias disponíveis.
Sugestões de horários ideais para realizar o treino com base no meu estilo de vida.
Uma dieta balanceada que apoie o meu objetivo fitness (ganhar massa muscular, perder gordura, ou manter o peso). """

Biotipo Corporal: Ectomorfo, Mesomorfo ou Endomorfo?
Reposta: Endomorfo.

Disponibilidade de Tempo: Quantos dias por semana você pode treinar? 1, 3 ou 5 dias?
Repostas: 3 dias.

Tipo de Exercício Preferido: Funcional, Maquinário, Peso Livre, Cardio ou HIIT?
Resposta: Funcional.

Objetivo Fitness: Ganhar massa muscular, perder gordura ou manter o peso?
Resposta: Ganhar massa muscular

# Retorno do chatbot - Utilizei o ChatGPT o1-preview

Olá! Com base nas suas informações, elaborei um plano de treino funcional de 3 dias, sugestões de horários e uma dieta balanceada para ajudá-lo a ganhar massa muscular.

---

### **Plano de Treino Funcional de 3 Dias**

**Dia 1: Parte Superior do Corpo**

1. **Flexões** – 3 séries de 12 repetições
2. **Remada Invertida** – 3 séries de 10 repetições
3. **Prancha com Elevação de Braço** – 3 séries de 10 repetições (cada braço)
4. **Burpees** – 3 séries de 8 repetições
5. **Flexão Pike (para ombros)** – 3 séries de 12 repetições

**Dia 2: Parte Inferior do Corpo**

1. **Agachamentos** – 3 séries de 15 repetições
2. **Afundos (Lunges)** – 3 séries de 12 repetições (cada perna)
3. **Levantamento Terra com Kettlebell** – 3 séries de 10 repetições
4. **Ponte de Glúteos** – 3 séries de 15 repetições
5. **Saltos no Caixote (Box Jumps)** – 3 séries de 8 repetições

**Dia 3: Corpo Inteiro e Core**

1. **Swing com Kettlebell** – 3 séries de 12 repetições
2. **Clean and Press com Kettlebell** – 3 séries de 10 repetições
3. **Mountain Climbers** – 3 séries de 20 repetições (10 cada perna)
4. **Russian Twists** – 3 séries de 15 repetições (cada lado)
5. **Burpee com Salto Vertical** – 3 séries de 8 repetições

**Dicas para o Treino:**

- **Aquecimento:** Antes de cada sessão, faça 5-10 minutos de aquecimento, como polichinelos ou corrida leve no lugar.
- **Alongamento:** Após o treino, alongue os principais grupos musculares trabalhados.
- **Progressão:** À medida que ganhar força, aumente gradualmente o número de repetições ou séries.

---

### **Sugestões de Horários Ideais para Treinar**

Para maximizar o ganho de massa muscular, é importante treinar quando você se sente mais disposto e energético. Aqui estão algumas considerações:

- **Horário Matinal (6h - 9h):** Treinar pela manhã pode aumentar a energia e o foco ao longo do dia.
- **Final da Tarde (16h - 19h):** Neste período, a temperatura corporal está mais alta, o que pode melhorar o desempenho muscular.
- **Consistência é Chave:** Escolha horários que se encaixem melhor na sua rotina diária para garantir consistência nos treinos.

---

### **Dieta Balanceada para Ganho de Massa Muscular**

Como um endomorfo, é importante focar em uma dieta rica em nutrientes que suporte o crescimento muscular sem acumular gordura excessiva.

**Macronutrientes Diários Recomendados:**

- **Proteínas:** 1,6 - 2,2 gramas por kg de peso corporal
- **Carboidratos Complexos:** Fornecem energia sustentada
- **Gorduras Saudáveis:** Importantes para a produção hormonal e saúde geral

**Plano Alimentar Diário Exemplo:**

**Café da Manhã:**

- Omelete de 3 ovos com espinafre e tomate
- 1 fatia de pão integral
- 1 porção de frutas vermelhas (morango, amora)

**Lanche da Manhã:**

- Iogurte grego sem açúcar com uma colher de sopa de mel
- Punhado de nozes ou amêndoas

**Almoço:**

- Peito de frango grelhado
- Quinoa ou arroz integral
- Salada mista com folhas verdes, cenoura e pepino
- Azeite de oliva e limão como tempero

**Lanche da Tarde:**

- Shake de proteína (whey protein) com água ou leite vegetal
- 1 banana

**Jantar:**

- Salmão assado ou filé de peixe
- Batata-doce cozida ou purê de batata-doce
- Brócolis e couve-flor no vapor

**Ceia (opcional):**

- Queijo cottage ou ricota com sementes de chia
- Chá de camomila ou outro chá sem cafeína

**Dicas Nutricionais Adicionais:**

- **Hidratação:** Beba pelo menos 2 litros de água ao longo do dia.
- **Refeições Frequentes:** Comer a cada 3 horas ajuda a manter o metabolismo ativo.
- **Evite Açúcares Simples:** Reduza o consumo de doces, refrigerantes e alimentos processados.
- **Suplementação:** Considere suplementos como creatina e BCAAs, após consultar um profissional de saúde.

---

### **Considerações Finais**

- **Descanso:** Garanta 7-9 horas de sono por noite para recuperação muscular.
- **Consistência:** Mantenha-se firme no plano para ver resultados ao longo do tempo.
- **Acompanhamento Profissional:** Se possível, consulte um nutricionista e um educador físico para um acompanhamento personalizado.
