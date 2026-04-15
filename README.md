# agente-de-organizacao-de-estudos
Projeto realizado no Bootcamp Bradesco da DIO -  O uso da Inteligência Artificial como uma verdadeira ferramenta de aprendizagem ativa!
Tecnologia usada: NotebookLM

CONTEXTO E OBJETIVOS
Caderno inteligente criado com o objetivo de otimizar o estudo diário, alimentado totalmente por métodos de estudos comprovados cientificamente e base de organização focada no notion. O objetivo do material é ajudar o dia a dia do estudante de qualquer área, criando cronogramas de estudo, analisando os métodos que fazem sentido para cada pessoa, resumo de conteúdos, planejamento semanal e mensal, sessões de foco e revisão espaçada.
------------------------------------------------------------------------------------------------------------------
CONCEITOS 
Técnica Feynman: método de aprendizado baseado em explicar de forma simples para garantir compreensão real.
Pomodoro: técnica de gestão de tempo com ciclos de foco e pausa.
Revisão Espaçada: estratégia de revisão em intervalos progressivos para fixação de conteúdo.
Recordação Ativa: prática de recuperar informações da memória sem consulta.
Modo Focado: estado de concentração intensa em uma tarefa.
Modo Difuso: estado mental relaxado que auxilia na assimilação de ideias.
Toggle (Notion): bloco que permite esconder e revelar conteúdo.
Callout (Notion): bloco visual usado para destacar informações importantes.
Banco de Dados (Notion): estrutura para organizar informações em formato de tabela, lista ou board.

------------------------------------------------------------------------------------------------------------------
PROMPTS REUTILIZÁVEIS
Organização de rotina
Crie um planejamento de estudos para hoje considerando [tempo disponível] e [matérias]. Priorize foco, pausas e revisão.

Cronograma semanal
Monte um cronograma de estudos semanal equilibrado com base nas seguintes matérias: [listar]. Inclua revisão espaçada e momentos de descanso.

Técnica Feynman
Explique o conteúdo [tema] de forma simples, como se fosse para uma criança, usando exemplos e analogias.

Revisão Espaçada
Crie um plano de revisão espaçada para o conteúdo [tema], considerando um período de [tempo].

Sessão Pomodoro
Organize uma sessão de estudos usando a técnica Pomodoro para a tarefa [atividade], incluindo pausas e metas por ciclo.

Organização no Notion
Estruture uma página no Notion para estudar [tema], incluindo seções, uso de toggles e organização de conteúdo.

Resumo inteligente
Resuma o conteúdo [tema] de forma clara, estruturada e objetiva, destacando os pontos principais.
    
Autoavaliação
Crie perguntas para testar meu conhecimento sobre [tema], utilizando o método de recordação ativa.
------------------------------------------------------------------------------------------------------------------
ENGENHARIA DE PROMPTS E CICATRIZES 
Versão 1 
Objetivo: criar um chat especialista em estudos e produtividade

Prompt utilizado: “Comporte-se como um especialista em estudos, produtividade e organização, ajudando com cronogramas, técnicas de estudo e organização do tempo.”

Resultado:
Respostas corretas, porém:
Muito genéricas
Pouco foco em ferramenta prática
Não direcionava para rotina real

Problema identificado: O prompt estava amplo demais, sem contexto de uso e sem restrição de comportamento.

Versão 2
Melhoria aplicada: Adição de contexto (Notion)
Definição de funções específicas

Prompt: “Comporte-se como um especialista em estudos, produtividade e organização no Notion. Ajude com organização diária, cronogramas, revisão espaçada e técnicas como Pomodoro.”

Resultado:
Respostas mais úteis
Começou a sugerir estrutura de organização
Já trouxe aplicações práticas

Problema:
Ainda respondia de forma “genérica de internet”
Linguagem às vezes formal demais
Não adaptava para rotina específica

Prompt refinado (versão final)

Melhorias aplicadas:

Definição clara de papel (secretária de estudos)
Definição de escopo (dia/semana/mês)
Definição de estilo de linguagem
Lista explícita do que pode fazer

Prompt final: “Comporte-se como um especialista em estudos, produtividade e organização, preferencialmente no Notion. Você deverá ajudar com organização diária, otimização do tempo e foco de acordo com as demandas passadas, podendo ser do dia, semana ou mês. Você poderá criar cronograma de estudos, revisão espaçada, técnicas como Pomodoro, organização no Notion e resumos. Funcione como uma secretária de estudos pessoal, sempre usando linguagem simples, sem emojis ou abreviações.”

Resultado:
Respostas muito mais estruturadas
Melhor direcionamento prático
Linguagem consistente
Mais aplicável ao dia a dia

O processo mostrou que a qualidade das respostas da IA depende diretamente da clareza e especificidade do prompt. A evolução do prompt permitiu transformar um assistente genérico em uma ferramenta prática de apoio aos estudos, com foco em organização, produtividade e aplicação real no dia a dia.

------------------------------------------------------------------------------------------------------------------
CURADORIA DE FONTES
FONTES DE VÍDEO:
https://youtu.be/vdj7RHWj568?si=RO0ff6LPu54AsOTq
https://youtu.be/bauTkFkx-YA?si=a2X7SRJuu47rDkWT
https://youtu.be/posTc56basM?si=-C84Dqtu5PpaPYxK
https://youtu.be/uWkQK9ytWe4?si=tyh96iVw1NR5YhM6
https://youtu.be/mHxGMVsy0JQ?si=kWGICoEa2O1n459k
https://youtu.be/6Ex2QcrFBlk?si=xh8RuJq9xxIofLk2
https://youtu.be/TVHUs67kwRk?si=7qKVVWMKmYw1vAfc
https://youtu.be/upMrjrq_53g?si=6B5BSveNADCVI_yV
https://www.youtube.com/watch?v=sgX24vZqVFIhttps://www.youtube.com/watch?v=vyH_H6ZCjrU
https://www.youtube.com/watch?v=OhfiiyptBLE
https://youtu.be/g9xEYTB82gM?si=Fq04_RaQMY62UNHQ
https://youtu.be/C7dEeg7vGiA?si=aS5O5a_Tl6KxH5o_
https://www.youtube.com/watch?v=1RxvQ3-0WoU

FONTES DE TEXTO: 
https://exame.com/carreira/guia-de-carreira/como-usar-a-tecnica-feynman-para-estudar-e-aprender-materias-dificeis/
https://www.bbc.com/portuguese/articles/cjdnn0r1pmro
https://conexao.pucminas.br/blog/dicas/tecnica-feynman/
https://www.publi.com.br/tecnica-pomodoro-foco-disciplina-e-mais-resultados-no-dia-a-dia/
https://conexao.pucminas.br/blog/dicas/metodo-pomodoro-de-estudo/
https://www.cnnbrasil.com.br/educacao/estudos-para-os-vestibulares-conheca-o-metodo-robinson-ou-epl2r/
https://www.cevconcursos.com.br/blog/blog/voce-conhece-o-metodo-robinson-epl2r-nao-entao-fique-por-dentro-de-mais-essa-importante-tecnica-de-estudos-168.html
https://guiadoestudante.abril.com.br/coluna/dicas-estudo/conheca-o-metodo-de-estudo-robinson/
https://conexao.pucminas.br/blog/dicas/metodo-cornell/
https://lsc.cornell.edu/how-to-study/taking-notes/cornell-note-taking-system/
https://pt.wikipedia.org/wiki/Método_Cornell
https://www.notion.com/pt/help/guides
https://www.oitchau.com.br/blog/como-usar-o-notion/
