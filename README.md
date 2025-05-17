# class-planner
Desafio imersão IA Alura + Gemini

# ✨ Gerador de Plano de Aula com Gemini e Agentes ✨

Seja bem-vindo ao meu projeto! 🎉 Este é um sistema inovador que utiliza o poder do modelo Gemini e uma arquitetura de agentes para automatizar a criação de planos de aula completos e personalizados.

📚 **Qual o problema que ele resolve?**

Criar planos de aula de qualidade leva tempo e exige pesquisa sobre conteúdo, atividades e formas de avaliação. Este projeto simplifica esse processo para professores e educadores, gerando planos de aula relevantes e alinhados com a BNCC de forma rápida e eficiente.

🚀 **Como funciona?**

O coração do sistema é um `PlanejadorPedagogico` que orquestra o trabalho de diferentes agentes especializados:

*   **Agente Conteúdo:** Sugere o conteúdo didático para a aula, baseado na série, disciplina e tema, alinhado com a BNCC.
*   **Agente Atividades:** Propõe atividades lúdicas e práticas adequadas para a série e tema.
*   **Agente Avaliação:** Sugere instrumentos de avaliação formativa e somativa para o tema.
*   **Agente Agenda:** Organiza o conteúdo, atividades e avaliações em um cronograma semanal.

Cada agente utiliza o modelo Gemini para gerar respostas criativas e contextualmente relevantes.

🔧 **Tecnologias Utilizadas:**

*   Google Gemini API
*   Google Agent Development Kit (ADK)
*   Python

💡 **Como usar:**

1.  Clone o repositório.
2.  Instale as dependências: `pip install -q google-genai google-adk`
3.  Obtenha sua API Key do Google Gemini e configure no Colab (usando `userdata.get('GOOGLE_API_KEY')`).
4.  Execute o código no Google Colab.
5.  O programa solicitará as informações da aula (Série, Disciplina, Tema e Duração).

🎁 **Resultados:**

O sistema irá gerar um plano de aula completo, com:

*   Conteúdo detalhado.
*   Sugestões de atividades práticas.
*   Sugestões de instrumentos de avaliação.
*   Um cronograma semanal organizado.

🏆 **Por que este projeto é especial?**

*   **Inovação:** Utiliza a combinação de modelos de linguagem avançados (Gemini) e arquitetura de agentes para resolver um problema prático na educação.
*   **Eficiência:** Automatiza um processo que consome muito tempo dos educadores.
*   **Criatividade:** Os agentes geram conteúdo e sugestões criativas e relevantes.
*   **Flexibilidade:** Permite personalizar o plano de aula com base nas necessidades específicas do usuário.

🔮 **Próximos passos (Ideias para futuras melhorias):**

*   Adicionar a possibilidade de o usuário refinar as sugestões dos agentes.
*   Expandir a base de conhecimento dos agentes para incluir mais disciplinas e níveis de ensino.
*   Desenvolver uma interface mais amigável (Web ou GUI).
*   Integrar com outras ferramentas educacionais.

👩‍🏫 **Contribuições:**

Sugestões e contribuições são muito bem-vindas! Se você tiver ideias para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Obrigado por conferir meu projeto! Espero que goste! 😊
