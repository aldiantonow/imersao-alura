# imersao-alura
#Sugestões de Animes com Agentes de IA
Este projeto utiliza agentes de IA para fornecer recomendações personalizadas de animes com base nas preferências do usuário. O sistema coleta informações sobre os gostos do usuário e, em seguida, utiliza três agentes de IA para analisar essas preferências, buscar animes correspondentes e refinar as sugestões.

# Funcionalidades
Análise de Perfil do Usuário: O sistema coleta as preferências do usuário através de um breve questionário, incluindo seus animes favoritos, gêneros preferidos, características valorizadas, preferências de duração e temas a evitar.
Busca Inteligente de Animes: Utilizando as informações do perfil do usuário, o sistema busca animes que correspondam aos seus gostos, considerando diversos critérios como gênero, estilo, características valorizadas e temas a evitar.
Revisão e Refinamento de Sugestões: As sugestões de animes são revisadas por um agente especializado para garantir a máxima compatibilidade com o perfil do usuário, oferecendo recomendações precisas e justificadas.

# Tecnologias Utilizadas
Python
Google Gemini API
Google ADK (Agents Development Kit)
Bibliotecas: google-genai, google-adk, requests

# Pré-requisitos
Chave da API do Google Gemini configurada como variável de ambiente (GOOGLE_API_KEY).
Python 3.6 ou superior.
Bibliotecas Python instaladas (verifique o notebook para as instalações).

# Como Usar
Execute o notebook Imersão_alura_Sugestões_de_animes_Agentes_IA.ipynb.
Responda às perguntas sobre suas preferências de anime quando solicitado.
O sistema fornecerá uma lista de recomendações de animes personalizadas.

# Estrutura do Código
O projeto é organizado em torno de três agentes de IA principais:
Agente Analisador: Responsável por coletar as preferências do usuário e criar um perfil estruturado.
Agente Buscador: Utiliza o perfil do usuário para buscar animes relevantes.
Agente Revisor: Revisa as sugestões do Agente Buscador e fornece uma lista final refinada.

# Contribuição
Contribuições são bem-vindas! Se você tiver alguma sugestão de melhoria ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.

# Autores
Audy Antonow e Andrus Antonow
