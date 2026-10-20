# Missão Samaúma – Detecção Orbital de Pistas Clandestinas na Amazônia
<p align="center">
  <img src="./Documentos/Img/SAMAUMA-LOGO.png" width="250" alt="Logo da Missão Samaúma">
</p>

## Introdução
A Amazônia desempenha um papel estratégico de extrema relevância global e nacional, abrigando a maior biodiversidade do planeta e recursos naturais de alto valor. Contudo, essa importância é 
ameaçada pela proliferação de pistas de pouso clandestinas, que funcionam como vetores para atividades ilícitas como garimpo ilegal, narcotráfico e desmatamento, comprometendo o equilíbrio ambiental,
social e a soberania nacional.
Estudos apontam que há mais pistas não homologadas do que oficiais na Amazônia Legal, formando uma infraestrutura paralela que impulsiona essas atividades ilegais.

Apesar dos esforços de fiscalização, o monitoramento por satélites convencionais enfrenta limitações significativas:
- Baixa frequência de revisita orbital, dificultando a detecção em tempo hábil.
- Alta latência entre a aquisição e o processamento das imagens.
- Custos elevados de obtenção e manutenção de imagens atualizadas.
- Diante desses desafios, a Missão Samaúma propõe o desenvolvimento de um CubeSat 1U de baixo custo com inteligência artificial embarcada capaz de realizar imageamento orbital autônomo e detecção
em tempo real de pistas clandestinas.

**O satélite processa as imagens diretamente em órbita e envia alertas com dados de localização e área estimada, reduzindo custos, latência e dependência de infraestrutura terrestre.
O projeto reforça a pesquisa em monitoramento ambiental com tecnologias acessíveis e contribui para o avanço da IA embarcada em CubeSats, com impacto direto na soberania e proteção da Amazônia.**

### Equipe e Responsabilidades

A Missão Samaúma é conduzida por dois estudantes de Engenharia de Computação do Instituto Nacional de Telecomunicações (INATEL), sob orientação técnica do Prof. Evandro César Vilas Boas.

### Membros, Funções e	Responsabilidades
- Mateus Ananias Duarte Lima	Software e IA embarcada	Desenvolvimento do algoritmo de detecção de pistas; implementação do sistema operacional de tempo real (RTOS); integração dos subsistemas via software.
- Daniele Letícia Pereira Sousa	Hardware e sistemas embarcados	Projeto e implementação dos subsistemas físicos (EPS, STR, Payload, COMMS, TCS, ADCS); integração e validação de hardware.

- Apesar da divisão de responsabilidades, o trabalho é conduzido de forma colaborativa e integrada, permitindo que ambos mantenham visão global do projeto e contribuam em múltiplas frentes técnicas.

## Descrição Operacional

A Missão Samaúma é estruturada em três etapas principais:
- Mapeamento e pesquisa inicial
- Identificação de áreas críticas com maior ocorrência de desmatamento, indicativas de potenciais pistas irregulares.
- Imageamento orbital via CubeSat
- Coleta de imagens nas regiões mapeadas, utilizando sensores ópticos embarcados.

### Processamento e análise por IA
O algoritmo embarcado processa as imagens diretamente no computador de bordo (OBC), distinguindo áreas de desmatamento comum de pistas clandestinas, e enviando alertas automáticos com coordenadas 
e área estimada.

## Tecnologias e Conceitos-Chave
- CubeSat 1U – Plataforma modular de baixo custo para missões orbitais.
- IA Embarcada (On-board Processing) – Reduz latência e dependência de links terrestres.
- RTOS (Real-Time Operating System) – Assegura eficiência e previsibilidade na execução das tarefas do satélite.
- Detecção Autônoma de Pistas – Uso de visão computacional e aprendizado de máquina para classificação de imagens orbitais.
