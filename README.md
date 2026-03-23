# 🎸 Roadmap REAPER: Do Zero ao Avançado (Powered by NotebookLM)

![Status](https://img.shields.io/badge/Status-Projeto%20Finalizado-green?style=for-the-badge)
![Tech](https://img.shields.io/badge/Google-NotebookLM-blue?style=for-the-badge)
![Topic](https://img.shields.io/badge/Audio-REAPER-orange?style=for-the-badge)

## 🎯 Contexto e Objetivos
Este projeto foi desenvolvido como parte de um desafio prático na **DIO**, explorando o uso da Inteligência Artificial **NotebookLM** como ferramenta de aprendizagem ativa. 

O tema escolhido foi a criação de um **Roadmap de Aprendizado do Zero para o software REAPER (Digital Audio Workstation)**. O objetivo é transformar documentações técnicas e tutoriais em um guia lógico, auxiliando o usuário a entender desde os pré-requisitos de hardware até as capacidades e limitações da ferramenta.

---

## 📚 Curadoria de Fontes
A base de conhecimento foi estruturada a partir de fontes oficiais e referências da comunidade de produção de áudio:

### 📄 Documentos e Manuais Técnicos (PDF)
* [Up and Running: REAPER User Guide v7.66 (Março/2026)](https://dlz.reaper.fm/userguide/ReaperUserGuide766.pdf)
* [REAPER 7.0: What’s New (Summary)](https://dlz.reaper.fm/userguide/WhatsNewReaper7Summary_r2.pdf)
* [REAPER Quick Start Guide](https://www.reaper.fm/guides/REAPER%20Quick%20Start.pdf)

### 🎥 Tutoriais e Vídeos Estruturantes (YouTube)
Processamento de transcrições de canais como **Adam Steel**, **Reapertips**, **Graviola Home Studio** e **Envato Tuts+**, focando em fundamentos, gravação de instrumentos e mixagem.

### 🌐 Recursos Adicionais da Comunidade
* **[REAPER Stash](https://stash.reaper.fm):** Temas, ícones e scripts.
* **[SWS Extensions](https://sws-extension.org):** Extensões vitais de workflow.
* **[ReaPack](https://reapack.com):** Gerenciador de pacotes e scripts.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

**Prompt Exploratório:** > "Liste os conhecimentos prévios desejados que o usuário deva ter para que tenha uma melhor experiência ao aprender o uso do software, os equipamentos mínimos necessários, assim como limitações de uso do programa e detalhe o que o usuário pode obter utilizando o software e o que o usuário NÃO poderá obter utilizando o software. Liste também as vantagens e desvantagens de optar pela utilização do Reaper."

**Dificuldades e Soluções (Troubleshooting):**
Sintetizei as informações detalhadas sobre o uso do REAPER para mitigar a curva de aprendizado íngreme:

1. **Conhecimentos Prévios:** Teoria musical básica, estrutura de arranjo, conceitos de áudio digital (bits, frequência) e noções de mixagem.
2. **Equipamentos Mínimos:** Computador (Win/Mac/Linux/RPi), Interface de Áudio (essencial para baixa latência), monitoração de qualidade e mouse com scroll.
3. **Potencial do Software:** Produção multitrilha profissional, Design de Som, edição de vídeo básica e customização total via Actions e Scripts.
4. **Limitações:** Instrumentos virtuais nativos são básicos (exige VSTs externos), sem renderização nativa para AAC e interface inicial intimidadora.
5. **Vantagens vs. Desvantagens:** - *Vantagens:* Estabilidade, preço acessível (US$ 60), portabilidade e atualizações frequentes.
   - *Desvantagens:* Curva de aprendizado elevada e visual padrão que exige customização.

---

## 📖 Miniguia de Estudo (Entrega Final)

Este miniguia consolidado foi elaborado com base no manual oficial e nos tutoriais especializados para facilitar seu aprendizado e revisão do REAPER.

### 1. Resumo Estruturado do Assunto

**A. Natureza e Configuração Inicial** O REAPER é uma Digital Audio Workstation (DAW) completa, multiplataforma e extremamente leve (~250MB). O primeiro passo crítico é configurar o driver **ASIO** (no Windows) para reduzir a latência. Taxas de amostragem padrão sugeridas: 44.1kHz (CD) ou 48kHz (Streaming/Vídeo).

**B. Interface e Fluxo de Trabalho** - **Timeline/Arrange View:** Organização de blocos de áudio/MIDI (Items).
- **Mixer Control Panel (MCP):** Ajuste de volumes, pan e efeitos.
- **Track Control Panel (TCP):** Controles de armar gravação, mute e solo.
- **Actions List:** O "sistema nervoso central" para buscar comandos e criar atalhos.

**C. Gravação e Edição de Áudio** A edição é **não-destrutiva** (preserva o arquivo original). Ferramentas essenciais incluem o **Ripple Editing** (move itens subsequentes automaticamente) e o uso de **Fades/Crossfades** automáticos para evitar cliques sonoros.

**D. MIDI e Instrumentos Virtuais** O REAPER não diferencia trilhas de áudio e MIDI. No Editor MIDI, as notas podem ser visualizadas como retângulos ou diamantes (ideal para bateria). É possível "humanizar" performances variando aleatoriamente o *Velocity*.

**E. Mixagem e Masterização** - **EQ (ReaEQ):** Moldar o tom e remover frequências conflitantes.
- **Compressão (ReaComp):** Controlar a dinâmica.
- **Ambiência:** Uso de Reverb e Delay via *Sends*.
- **Masterização:** Polimento final e ajuste de volume para padrões competitivos usando o **ReaLimit**.

---

### 2. Glossário de Principais Conceitos
* **Action List:** Menu com milhares de funções para automação e atalhos.
* **ASIO:** Driver de alta performance para baixa latência.
* **Automation/Envelopes:** Linhas para variar parâmetros automaticamente no tempo.
* **Buffer Size:** Tamanho do bloco de memória; afeta latência vs. uso de CPU.
* **Glue Items:** Funde vários itens em um único novo arquivo.
* **Non-Destructive Editing:** Sistema que mantém os arquivos originais intactos no HD.
* **SWS Extensions / ReaPack:** Scripts da comunidade que expandem as funções do software.

---

### 3. Conjunto de Prompts para Revisões Futuras
* **Resolução de Problemas:** *"Estou com eco (ghosting) na gravação. Com base na monitoração e ASIO, como corrigir?"*
* **Workflow:** *"Como criar uma Custom Action que divida um item e remova o silêncio (Auto-trim) simultaneamente?"*
* **Mixagem:** *"Como aplicar ReaEQ e ReaComp para resolver problemas de 'mascaramento de frequência'?"*
* **Masterização:** *"Crie um checklist de 5 passos para masterizar no REAPER usando apenas plugins nativos."*

---
📅 **Data:** Março de 2026  
👤 **Autor:** Lucas Tadeu de Moura  
🛠️ **Ferramentas:** NotebookLM, GitHub, REAPER DAW.
