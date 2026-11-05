<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quiz Interativo: Verbos e Sintaxe</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
    }
    .badge-bounce {
      animation: bounce 0.6s ease infinite alternate;
    }
    @keyframes bounce {
      from { transform: translateY(0); }
      to { transform: translateY(-4px); }
    }
  </style>
</head>
<body class="bg-slate-900 text-slate-100 min-h-screen flex flex-col justify-between p-4 sm:p-6">

  <!-- Container Principal -->
  <div class="max-w-3xl w-full mx-auto my-auto">
    
    <!-- Cabeçalho / Barra de Progresso -->
    <header class="mb-6 bg-slate-800/80 p-5 rounded-2xl border border-slate-700/60 shadow-xl backdrop-blur-sm">
      <div class="flex justify-between items-center mb-3">
        <span class="text-xs font-bold uppercase tracking-wider text-indigo-400 bg-indigo-950/60 px-3 py-1 rounded-full border border-indigo-800/50">
          Treino Sintático • 9º Ano
        </span>
        <span id="question-counter" class="text-sm font-semibold text-slate-300">
          Questão 1 de 10
        </span>
      </div>
      <!-- Barra de progresso -->
      <div class="w-full bg-slate-700/70 h-3 rounded-full overflow-hidden p-0.5 border border-slate-600/40">
        <div id="progress-bar" class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 h-full rounded-full transition-all duration-500" style="width: 10%;"></div>
      </div>
    </header>

    <!-- Área Principal da Questão (Card) -->
    <main id="quiz-card" class="bg-slate-800 p-6 sm:p-8 rounded-3xl border border-slate-700 shadow-2xl relative overflow-hidden">
      
      <!-- Frase Central -->
      <div class="text-center mb-8">
        <span class="text-xs text-slate-400 uppercase tracking-widest font-semibold block mb-2">Análise da Frase:</span>
        <div id="sentence-display" class="text-2xl sm:text-3xl font-extrabold text-white tracking-wide bg-slate-900/60 py-4 px-6 rounded-2xl border border-slate-700/80 inline-block shadow-inner">
          <!-- A frase será inserida dinamicamente -->
        </div>
      </div>

      <!-- Formulário de Análise -->
      <div class="space-y-5">
        
        <!-- Bloco Sujeito -->
        <div id="block-sujeito" class="bg-slate-900/40 p-4 rounded-xl border border-slate-700/50">
          <label class="block text-sm font-bold text-slate-300 mb-2 flex items-center gap-2">
            <span class="w-2 h-2 rounded-full bg-emerald-400"></span>
            1. Quem é o <strong class="text-emerald-400">SUJEITO</strong> e qual a função?
          </label>
          <div id="options-sujeito" class="grid grid-cols-1 sm:grid-cols-2 gap-2">
            <!-- Opções inseridas via JS -->
          </div>
        </div>

        <!-- Bloco Verbo -->
        <div id="block-verbo" class="bg-slate-900/40 p-4 rounded-xl border border-slate-700/50">
          <label class="block text-sm font-bold text-slate-300 mb-2 flex items-center gap-2">
            <span class="w-2 h-2 rounded-full bg-indigo-400"></span>
            2. Qual é a classificação do <strong class="text-indigo-400">VERBO</strong>?
          </label>
          <div id="options-verbo" class="grid grid-cols-1 sm:grid-cols-3 gap-2">
            <!-- Opções inseridas via JS -->
          </div>
        </div>

        <!-- Bloco Termo Restante -->
        <div id="block-termo" class="bg-slate-900/40 p-4 rounded-xl border border-slate-700/50">
          <label class="block text-sm font-bold text-slate-300 mb-2 flex items-center gap-2">
            <span class="w-2 h-2 rounded-full bg-amber-400"></span>
            3. Como se classifica a <strong class="text-amber-400">PARTE FINAL</strong> da frase?
          </label>
          <div id="options-termo" class="grid grid-cols-1 sm:grid-cols-2 gap-2">
            <!-- Opções inseridas via JS -->
          </div>
        </div>

      </div>

      <!-- Botão Enviar -->
      <div class="mt-8 flex justify-end">
        <button id="btn-submit" onclick="checkAnswer()" class="w-full sm:w-auto bg-gradient-to-r from-indigo-500 to-purple-600 hover:from-indigo-600 hover:to-purple-700 text-white font-bold py-3.5 px-8 rounded-xl shadow-lg hover:shadow-indigo-500/25 transition-all transform active:scale-95 disabled:opacity-50 disabled:cursor-not-allowed">
          Conferir Resposta
        </button>
      </div>

      <!-- Overlay de Feedback (Acerto / Erro) -->
      <div id="feedback-modal" class="hidden absolute inset-0 bg-slate-900/95 backdrop-blur-md p-6 sm:p-8 flex flex-col justify-between z-20 transition-all duration-300">
        <div>
          <div id="feedback-badge" class="inline-flex items-center gap-2 px-4 py-2 rounded-full font-bold text-sm mb-4">
            <!-- Badge de Acerto/Erro -->
          </div>
          <h3 id="feedback-title" class="text-2xl font-extrabold mb-3"></h3>
          <p id="feedback-explanation" class="text-slate-300 leading-relaxed text-base sm:text-lg bg-slate-800/80 p-5 rounded-2xl border border-slate-700"></p>
        </div>
        <div class="mt-6 flex justify-end">
          <button id="btn-next" onclick="nextQuestion()" class="w-full sm:w-auto bg-white text-slate-900 hover:bg-slate-100 font-bold py-3.5 px-8 rounded-xl shadow-lg transition-all transform active:scale-95">
            Próxima Questão ➔
          </button>
        </div>
      </div>

    </main>

    <!-- Card de Resultado Final (Invisível no início) -->
    <section id="results-card" class="hidden bg-slate-800 p-8 rounded-3xl border border-slate-700 shadow-2xl text-center">
      <div class="w-20 h-20 bg-gradient-to-tr from-indigo-500 to-purple-500 rounded-full flex items-center justify-center mx-auto mb-6 shadow-xl shadow-indigo-500/20">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
      </div>
      <h2 class="text-3xl font-extrabold text-white mb-2">Treino Concluído!</h2>
      <p class="text-slate-400 mb-6">Confira abaixo o seu desempenho final:</p>

      <div class="grid grid-cols-2 gap-4 max-w-md mx-auto mb-8">
        <div class="bg-slate-900/60 p-4 rounded-2xl border border-slate-700">
          <span class="text-xs text-slate-400 font-semibold block uppercase">Acertos</span>
          <span id="final-score" class="text-3xl font-extrabold text-emerald-400">0 / 10</span>
        </div>
        <div class="bg-slate-900/60 p-4 rounded-2xl border border-slate-700">
          <span class="text-xs text-slate-400 font-semibold block uppercase">Aproveitamento</span>
          <span id="final-percentage" class="text-3xl font-extrabold text-indigo-400">0%</span>
        </div>
      </div>

      <p id="final-message" class="text-slate-300 font-medium mb-8 max-w-lg mx-auto leading-relaxed"></p>

      <button onclick="restartQuiz()" class="bg-gradient-to-r from-indigo-500 to-purple-600 hover:from-indigo-600 hover:to-purple-700 text-white font-bold py-3.5 px-8 rounded-xl shadow-lg transition-all transform active:scale-95">
        Refazer o Quiz ↺
      </button>
    </section>

  </div>

  <footer class="mt-8 text-center text-xs text-slate-500 font-medium">
    Estudo Prático de Português • Verbo Transitivo, Intransitivo e de Ligação
  </footer>

  <script>
    // Banco de dados das 10 questões
    const questions = [
      {
        sentence: "Ela comprou um livro.",
        parts: { sujeito: "Ela", verbo: "comprou", complemento: "um livro" },
        correct: {
          sujeito: "sujeito",
          verbo: "transitivo",
          termo: "complemento"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'Ela' é o Sujeito" },
            { value: "predicado", label: "'Ela' é Predicativo" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "complemento", label: "'um livro' é Complemento (Objeto)" },
            { value: "predicativo", label: "'um livro' é Predicativo" },
            { value: "nenhum", label: "Não precisa de nada" }
          ]
        },
        explanation: "O verbo 'comprou' sozinho deixa a pergunta: 'comprou o quê?'. Quem compra, compra algo! Por isso ele é **Transitivo** e precisa do complemento 'um livro'."
      },
      {
        sentence: "O bebê dormiu.",
        parts: { sujeito: "O bebê", verbo: "dormiu", complemento: "Nenhum" },
        correct: {
          sujeito: "sujeito",
          verbo: "intransitivo",
          termo: "nenhum"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'O bebê' é o Sujeito" },
            { value: "objeto", label: "'O bebê' é Objeto" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "nenhum", label: "Não há complemento (sentido completo)" },
            { value: "complemento", label: "Possui complemento" }
          ]
        },
        explanation: "O verbo 'dormiu' já entrega todo o sentido da ação. Ninguém pergunta 'dormiu o quê?'. Logo, é um **Verbo Intransitivo**."
      },
      {
        sentence: "O bolo parece delicioso.",
        parts: { sujeito: "O bolo", verbo: "parece", complemento: "delicioso" },
        correct: {
          sujeito: "sujeito",
          verbo: "ligacao",
          termo: "predicativo"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'O bolo' é o Sujeito" },
            { value: "verbo", label: "'O bolo' é o Verbo" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "predicativo", label: "'delicioso' é Predicativo (Estado/Qualidade)" },
            { value: "complemento", label: "'delicioso' é Objeto" }
          ]
        },
        explanation: "O verbo 'parece' não indica uma ação, ele só serve para LIGAR o sujeito 'O bolo' à sua qualidade ('delicioso'). Por isso é um **Verbo de Ligação** e 'delicioso' é o **Predicativo do Sujeito**."
      },
      {
        sentence: "Eles comeram uma pizza.",
        parts: { sujeito: "Eles", verbo: "comeram", complemento: "uma pizza" },
        correct: {
          sujeito: "sujeito",
          verbo: "transitivo",
          termo: "complemento"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'Eles' é o Sujeito" },
            { value: "predicativo", label: "'Eles' é Predicativo" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "complemento", label: "'uma pizza' é Complemento" },
            { value: "predicativo", label: "'uma pizza' é Predicativo" }
          ]
        },
        explanation: "Quem come, come algo! O verbo 'comeram' exige a pergunta 'comeram o quê?'. Por isso é **Transitivo** e 'uma pizza' é o seu complemento."
      },
      {
        sentence: "Os alunos correram rapidamente.",
        parts: { sujeito: "Os alunos", verbo: "correram", complemento: "rapidamente" },
        correct: {
          sujeito: "sujeito",
          verbo: "intransitivo",
          termo: "adverbio"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'Os alunos' é o Sujeito" },
            { value: "objeto", label: "'Os alunos' é Objeto" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "adverbio", label: "'rapidamente' é Modo (Circunstância)" },
            { value: "complemento", label: "'rapidamente' é Complemento Obrigatório" }
          ]
        },
        explanation: "'Correram' tem sentido completo! A palavra 'rapidamente' apenas mostra o MODO como correram. Termos que indicam tempo, modo ou lugar são detalhes extras, logo o verbo é **Intransitivo**."
      },
      {
        sentence: "A professora ficou feliz.",
        parts: { sujeito: "A professora", verbo: "ficou", complemento: "feliz" },
        correct: {
          sujeito: "sujeito",
          verbo: "ligacao",
          termo: "predicativo"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'A professora' é o Sujeito" },
            { value: "objeto", label: "'A professora' é o Objeto" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "predicativo", label: "'feliz' é Predicativo do Sujeito" },
            { value: "complemento", label: "'feliz' é Complemento da ação" }
          ]
        },
        explanation: "O verbo 'ficou' liga o sujeito 'A professora' ao seu estado 'feliz'. Como apenas conecta uma característica ao sujeito, trata-se de um **Verbo de Ligação**."
      },
      {
        sentence: "O menino caiu.",
        parts: { sujeito: "O menino", verbo: "caiu", complemento: "Nenhum" },
        correct: {
          sujeito: "sujeito",
          verbo: "intransitivo",
          termo: "nenhum"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'O menino' é o Sujeito" },
            { value: "predicativo", label: "'O menino' é Predicativo" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "nenhum", label: "Não há complemento" },
            { value: "complemento", label: "Possui complemento" }
          ]
        },
        explanation: "O verbo 'caiu' encerra a ação com sentido total. Não necessita de complemento para ser entendido, portanto é **Intransitivo**."
      },
      {
        sentence: "Nós lemos o poema.",
        parts: { sujeito: "Nós", verbo: "lemos", complemento: "o poema" },
        correct: {
          sujeito: "sujeito",
          verbo: "transitivo",
          termo: "complemento"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'Nós' é o Sujeito" },
            { value: "verbo", label: "'Nós' é o Verbo" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "complemento", label: "'o poema' é Complemento (Objeto)" },
            { value: "predicativo", label: "'o poema' é Predicativo" }
          ]
        },
        explanation: "Quem lê, lê algo! 'Lemos' necessita da informação 'o quê?'. Logo, 'lemos' é um **Verbo Transitivo** e 'o poema' é o complemento."
      },
      {
        sentence: "Você está cansado.",
        parts: { sujeito: "Você", verbo: "está", complemento: "cansado" },
        correct: {
          sujeito: "sujeito",
          verbo: "ligacao",
          termo: "predicativo"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'Você' é o Sujeito" },
            { value: "objeto", label: "'Você' é o Objeto" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "predicativo", label: "'cansado' é Predicativo (Estado)" },
            { value: "complemento", label: "'cansado' é Objeto" }
          ]
        },
        explanation: "'Está' apenas junta o sujeito 'Você' ao estado temporário 'cansado'. Trata-se de um **Verbo de Ligação** e 'cansado' é o **Predicativo**."
      },
      {
        sentence: "O passarinho voou longe.",
        parts: { sujeito: "O passarinho", verbo: "voou", complemento: "longe" },
        correct: {
          sujeito: "sujeito",
          verbo: "intransitivo",
          termo: "adverbio"
        },
        options: {
          sujeito: [
            { value: "sujeito", label: "'O passarinho' é o Sujeito" },
            { value: "objeto", label: "'O passarinho' é o Objeto" }
          ],
          verbo: [
            { value: "transitivo", label: "Verbo Transitivo" },
            { value: "intransitivo", label: "Verbo Intransitivo" },
            { value: "ligacao", label: "Verbo de Ligação" }
          ],
          termo: [
            { value: "adverbio", label: "'longe' indica Lugar (Circunstância)" },
            { value: "complemento", label: "'longe' é Complemento Obrigatório" }
          ]
        },
        explanation: "Quem voa, simplesmente voa! A palavra 'longe' apenas dá a ideia do LUGAR (circunstância). O verbo 'voou' tem sentido completo sozinho, sendo **Intransitivo**."
      }
    ];

    let currentQuestion = 0;
    let score = 0;
    let selectedAnswers = { sujeito: null, verbo: null, termo: null };

    function loadQuestion() {
      const q = questions[currentQuestion];
      selectedAnswers = { sujeito: null, verbo: null, termo: null };
      
      // Atualizar progresso
      document.getElementById('question-counter').innerText = `Questão ${currentQuestion + 1} de ${questions.length}`;
      document.getElementById('progress-bar').style.width = `${((currentQuestion + 1) / questions.length) * 100}%`;
      
      // Atualizar Frase
      document.getElementById('sentence-display').innerText = q.sentence;

      // Renderizar Opções para Sujeito
      renderOptions('options-sujeito', q.options.sujeito, 'sujeito');
      // Renderizar Opções para Verbo
      renderOptions('options-verbo', q.options.verbo, 'verbo');
      // Renderizar Opções para Termo Restante
      renderOptions('options-termo', q.options.termo, 'termo');

      // Resetar Modal de Feedback
      document.getElementById('feedback-modal').classList.add('hidden');
    }

    function renderOptions(containerId, optionsList, category) {
      const container = document.getElementById(containerId);
      container.innerHTML = '';
      
      optionsList.forEach(opt => {
        const btn = document.createElement('button');
        btn.type = 'button';
        btn.className = `option-btn-${category} text-left p-3 rounded-lg border border-slate-700 bg-slate-800 hover:bg-slate-700/80 text-xs sm:text-sm font-medium transition-all text-slate-300`;
        btn.innerText = opt.label;
        btn.onclick = () => selectOption(category, opt.value, btn);
        container.appendChild(btn);
      });
    }

    function selectOption(category, value, element) {
      selectedAnswers[category] = value;
      
      // Estilizar selecionado
      const buttons = document.querySelectorAll(`.option-btn-${category}`);
      buttons.forEach(btn => {
        btn.classList.remove('bg-indigo-600', 'border-indigo-400', 'text-white', 'shadow-md');
        btn.classList.add('bg-slate-800', 'border-slate-700', 'text-slate-300');
      });

      element.classList.remove('bg-slate-800', 'border-slate-700', 'text-slate-300');
      element.classList.add('bg-indigo-600', 'border-indigo-400', 'text-white', 'shadow-md');
    }

    function checkAnswer() {
      // Verificar se tudo foi respondido
      if (!selectedAnswers.sujeito || !selectedAnswers.verbo || !selectedAnswers.termo) {
        alert("Por favor, selecione uma opção para cada um dos 3 itens da frase!");
        return;
      }

      const q = questions[currentQuestion];
      const isCorrect = (
        selectedAnswers.sujeito === q.correct.sujeito &&
        selectedAnswers.verbo === q.correct.verbo &&
        selectedAnswers.termo === q.correct.termo
      );

      const modal = document.getElementById('feedback-modal');
      const badge = document.getElementById('feedback-badge');
      const title = document.getElementById('feedback-title');
      const explanation = document.getElementById('feedback-explanation');

      if (isCorrect) {
        score++;
        badge.className = "inline-flex items-center gap-2 px-4 py-2 rounded-full font-bold text-sm mb-4 bg-emerald-500/20 text-emerald-400 border border-emerald-500/30";
        badge.innerHTML = "✓ RESPOSTA CORRETA";
        title.innerText = "Excelente! Você mandou muito bem!";
        title.className = "text-2xl font-extrabold mb-3 text-emerald-400";
      } else {
        badge.className = "inline-flex items-center gap-2 px-4 py-2 rounded-full font-bold text-sm mb-4 bg-rose-500/20 text-rose-400 border border-rose-500/30";
        badge.innerHTML = "✕ ATENÇÃO AO DETALHE";
        title.innerText = "Ops! Não foi bem assim desta vez.";
        title.className = "text-2xl font-extrabold mb-3 text-rose-400";
      }

      // Formatando a explicação usando markdown simples convertida para HTML
      let formattedExp = q.explanation.replace(/\*\*(.*?)\*\*/g, '<strong class="text-indigo-300 font-semibold">$1</strong>');
      explanation.innerHTML = formattedExp;

      modal.classList.remove('hidden');
    }

    function nextQuestion() {
      currentQuestion++;
      if (currentQuestion < questions.length) {
        loadQuestion();
      } else {
        showResults();
      }
    }

    function showResults() {
      document.getElementById('quiz-card').classList.add('hidden');
      document.querySelector('header').classList.add('hidden');
      
      const resultsCard = document.getElementById('results-card');
      resultsCard.classList.remove('hidden');

      const percentage = Math.round((score / questions.length) * 100);
      document.getElementById('final-score').innerText = `${score} / ${questions.length}`;
      document.getElementById('final-percentage').innerText = `${percentage}%`;

      const msgElement = document.getElementById('final-message');
      if (percentage >= 80) {
        msgElement.innerText = "Parabéns! Você dominou completamente a diferença entre Verbos Transitivos, Intransitivos e de Ligação! Está mais do que pronto para a prova!";
      } else if (percentage >= 50) {
        msgElement.innerText = "Muito bom! Você já entendeu a maioria dos conceitos. Faça mais um treino rápido para fixar 100% dos detalhes!";
      } else {
        msgElement.innerText = "Vale a pena revisar mais um pouquinho! Lembre-se: Verbo Transitivo pede complemento, Intransitivo já vem completo e de Ligação apenas conecta a uma qualidade.";
      }
    }

    function restartQuiz() {
      currentQuestion = 0;
      score = 0;
      document.getElementById('results-card').classList.add('hidden');
      document.querySelector('header').classList.remove('hidden');
      document.getElementById('quiz-card').classList.remove('hidden');
      loadQuestion();
    }

    // Inicializar na primeira questão quando a página carregar
    window.onload = function() {
      loadQuestion();
    };
  </script>
</body>
</html>
