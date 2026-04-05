🎵 SÓ-LÁMENTO — Sistema Educacional de Música

> Plataforma educacional interativa para aprendizado de fundamentos musicais, vídeo, animação e tecnologia MIDI.

---

📋 Sobre o Projeto

O **SÓ-LÁMENTO** é um software educacional desenvolvido em HTML, CSS e JavaScript puro, voltado para o ensino de conceitos de música digital e multimídia. A aplicação é totalmente executada no navegador, sem necessidade de instalação ou dependências externas.

---

🗂️ Estrutura do Projeto

```
SoftwareEducacional-main/
├── index.html        # Página principal e estrutura da aplicação
├── style.css         # Estilização da interface
├── script.js         # Lógica de navegação, quiz e síntese de áudio
└── media/
    ├── desenho.png         # Ícone/logo da aplicação
    ├── baner.png           # Banner da interface
    ├── animacao.gif        # Animação 2D demonstrativa
    ├── animacao.mp4        # Vídeo de animação
    ├── videoEditado.mp4    # Vídeo editado para a seção de conteúdo
    ├── video.mp4           # Vídeo adicional
    ├── musica.mp3          # Exemplo de música MIDI
    ├── vocal.mp3           # Exemplo de voz sintetizada
    └── voz sintetizada.mp3 # Exemplo adicional de síntese de voz
```

---

🚀 Como Executar

Por ser uma aplicação web estática, basta abrir o arquivo `index.html` diretamente no navegador:

```bash
# Clone ou extraia o projeto
# Navegue até a pasta do projeto e abra o arquivo principal
open index.html
```

> **Recomendação:** Para melhor compatibilidade com os recursos de áudio e vídeo, utilize navegadores modernos como Google Chrome, Firefox ou Microsoft Edge.

---

📚 Módulos de Conteúdo

🎼 Fundamentos de Música
Apresenta os conceitos básicos da teoria musical:
- **Notas musicais** — Dó, Ré, Mi, Fá, Sol com visualização em pentagrama SVG
- **Escala musical** — representação gráfica e interativa
- **Conceitos teóricos** — nota, escala, ritmo e timbre
- **Piano interativo** — permite tocar notas sintetizadas diretamente no navegador usando a Web Audio API

🎬 Vídeo e Animação
Explica os principais tipos de conteúdo audiovisual:
- **Animação 2D Tradicional** — técnica quadro a quadro
- **Animação 3D** — modelagem em espaço virtual
- **Vídeo Vlog** — formato pessoal e informal
- **Vídeo Tutorial** — instrução passo a passo

Inclui exibição de vídeo e animação GIF demonstrativos.

🎹 MIDI — Musical Instrument Digital Interface
Aborda o padrão de comunicação entre instrumentos digitais:
- O que é o protocolo MIDI
- Mensagens, velocidade e duração de notas
- Vantagens do formato (arquivos leves e editáveis)
- Aplicações em produção musical, jogos e educação
- Exemplos de áudio: música MIDI e voz sintetizada

🤔 Quiz Interativo
Sistema de avaliação com banco de 19 questões sobre todos os temas abordados. A cada rodada, são sorteadas 5 perguntas aleatórias. Ao final, o aluno recebe:
- Percentual de acerto com feedback personalizado
- Revisão detalhada de todas as respostas
- Opção de refazer o quiz com novas perguntas sorteadas

---

⚙️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura e semântica da aplicação |
| CSS3 | Estilização, animações e layout responsivo |
| JavaScript | Navegação entre páginas, lógica do quiz e síntese de áudio |
| Web Audio API | Síntese e reprodução de notas musicais no navegador |
| SVG | Visualização do pentagrama e notas musicais |

---

🎯 Funcionalidades

- Navegação entre módulos sem recarregar a página (SPA)
- Piano virtual com síntese de áudio em tempo real (envelope ADSR)
- Quiz com sorteio aleatório de perguntas e correção automática
- Barra de progresso durante o quiz
- Revisão das respostas ao final de cada rodada
- Reprodução de vídeos e áudios diretamente na interface

---

🖥️ Compatibilidade

Aplicação compatível com navegadores modernos que suportam:
- Web Audio API
- HTML5 `<video>` e `<audio>`
- ES6+ (let, const, arrow functions, spread operator)
