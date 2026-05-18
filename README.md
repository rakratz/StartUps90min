## 🚀 Refinando a Ideia: O "Lifestyle Match" Imobiliário

Em vez de vender a ideia apenas como "um portal de serviços", vamos empacotá-la com um pitch atraente de startup.

* **Nome Conceito:** *VibeHome* ou *Habitapp*
* **A Dor do Cliente:** Portais tradicionais focam em "3 quartos, 2 banheiros". Mas o cliente moderno quer saber: *"Consigo treinar pesado na academia do prédio?", "Tem um ecossistema pet friendly por perto?", "O condomínio tem lavanderia Omo ou mercado pegue-pague?"*.
* **A Solução Startup:** O primeiro marketplace imobiliário baseado em **estilo de vida e infraestrutura de serviços**.
* **O Diferencial da Startup (Monetização & Escala):** O portal não cobra apenas pelo anúncio. Ele cria um **ecossistema**. Condomínios e proprietários ganham um selo de pontuação (ex: *Selo Pet Prime*, *Selo Home Office Advanced*) se fecharem parcerias com fornecedores locais (lavanderias, redes de academia, mercados autônomos).

---

## 🛠️ Trilha de Prompts Incrementais (Para o AI Studio)

No workshop, você pode abrir o AI Studio (usando o modelo Gemini mais recente, como o Gemini 1.5 Pro ou Flash) e mostrar como a IA atua como co-fundadora da startup, evoluindo a ideia passo a passo.

### Passo 1: O Brainstorming e Validação da Ideia

> **Objetivo do Prompt:** Mostrar como usar a IA para validar o modelo de negócios e criar o Canvas da startup em segundos.

**Prompt:**

```text
Atue como um especialista em startups e capital de risco. Estou criando uma startup imobiliária chamada "VibeHome". Ao contrário dos portais tradicionais, o foco é o "estilo de vida" e os serviços do condomínio/região (ex: se tem academia completa, portaria eletrônica, parcerias com mercados locais, lavanderia compartilhada). 

Por favor, gere:
1. Um pitch de elevador (Elevator Pitch) de 30 segundos para investidores.
2. Três possíveis fontes de receita (Business Model) além do anúncio tradicional.
3. Quem seria o nosso "Early Adopter" (perfil do cliente ideal).

```

### Passo 2: Transformando Ideia em Dados (Engenharia de Prompt / System Instructions)

> **Objetivo do Prompt:** Mostrar o poder do AI Studio em gerar dados estruturados (JSON) que um desenvolvedor usaria para alimentar o aplicativo.

**Prompt:**

```text
Agora, preciso simular a nossa base de dados inicial. Atue como um gerador de dados JSON para a VibeHome. 
Gere um JSON com uma lista de 3 imóveis fictícios em São Paulo. Cada imóvel deve conter:
- Id, Endereço, Preço de locação.
- Uma lista de "Tags de Estilo de Vida" (ex: "Gym_Hardcore", "Pet_Lover", "Coworking_Premium").
- Um campo "Parcerias Ativas" listando quais serviços já estão integrados naquele condomínio (ex: "Mercado Autônomo Hirota", "Lavanderia Omo").

Formate estritamente em JSON válido.

```

### Passo 3: Criando a Experiência do Usuário (Copywriting da Interface)

> **Objetivo do Prompt:** Mostrar como a IA ajuda a desenhar a interface e a comunicação com o cliente (UX Writing).

**Prompt:**

```text
Vamos criar a tela inicial do nosso portal. Preciso que você escreva os textos (copywriting) para a interface do usuário:
1. O título principal (Headline) que vai impactar o usuário no site.
2. Um subtítulo explicativo.
3. Três opções de botões de filtro baseados em estilo de vida (ex: "Quero focar na saúde", "Trabalho de casa", etc.) com uma breve descrição para cada um.

```

### Passo 4: O "Modo Avançado" - O Chatbot Corretor (System Prompt)

> **Objetivo do Prompt:** Mostrar a principal funcionalidade do AI Studio — definir uma **System Instruction** para criar um agente personalizado.
> *Dica para o workshop: Cole o texto abaixo no campo "System Instructions" do AI Studio e teste no chat ao vivo com o público.*

**System Instruction para colocar no AI Studio:**

```text
Você é o "VibeBot", o assistente virtual de inteligência artificial do portal imobiliário VibeHome. Seu objetivo não é apenas perguntar quantos quartos o usuário quer, mas entender o ESTILO DE VIDA dele.

Diretrizes de comportamento:
1. Seja amigável, moderno e focado em serviços.
2. Pergunte sobre a rotina do usuário (se ele treina, se tem pets, se trabalha em home office, se cozinha ou prefere delivery).
3. Com base nas respostas, sugira os "serviços obrigatórios" que o condomínio dele precisa ter e como a VibeHome vai encontrar isso.

```

---

## ⏱️ Cronograma Sugerido para os 90 Minutos

Para você não se perder no tempo durante o workshop, aqui está uma sugestão de divisão:

* **00' - 15': Introdução & O Problema** (Apresentação do conceito da startup "VibeHome" e por que o mercado imobiliário tradicional está desatualizado).
* **15' - 30': Apresentação do AI Studio** (Tour rápido pela interface: System Instructions, Temperature, Modelos Pro vs Flash).
* **30' - 50': Mão na Massa - Validação e Negócio** (Execução dos **Passos 1 e 2**. Mostre a IA gerando o negócio e o JSON).
* **50' - 75': Prototipagem de Funcionalidade** (Execução dos **Passos 3 e 4**. Abra o chat com o *System Prompt* configurado e peça para alguém da plateia falar seu estilo de vida para o bot responder).
* **75' - 90': Conclusão & Próximos Passos** (Como transformar isso em um MVP real usando ferramentas No-Code + API do Gemini e Q&A).
