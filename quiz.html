<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Are you a human being?</title>
  <style>
    body {
      background-color: #0a0a0a;
      color: #d6d6d6;
      font-family: 'Courier New', monospace;
      text-align: center;
      padding: 60px 20px;
    }
    .question {
      font-size: 1.5em;
      margin-bottom: 30px;
    }
    .choices {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
    }
    button {
      background: none;
      border: 1px solid #555;
      color: #7aa2ff;
      padding: 10px 20px;
      font-size: 1em;
      cursor: pointer;
      transition: all 0.3s;
    }
    button:hover {
      background-color: #1a1a1a;
      border-color: #7aa2ff;
      filter: brightness(1.3);
    }
    .hidden { display: none; }
    .back-home {
      margin-top: 50px;
      display: inline-block;
      color: #7aa2ff;
      text-decoration: none;
      border: 1px solid #7aa2ff;
      padding: 8px 16px;
      transition: 0.3s;
    }
    .back-home:hover {
      background-color: #7aa2ff;
      color: #0a0a0a;
    }
  </style>
</head>
<body>
  <div id="quiz">
    <div class="question" id="question">Are you a human being?</div>
    <div class="choices" id="choices"></div>
  </div>

  <a href="index.html" id="backHome" class="back-home hidden">← Back to Home</a>

  <script>
    const quiz = {
      question: "Are you a human being?",
      options: {
        "Yes": {
          question: "Are you alive?",
          options: {
            "Yes": {
              question: "Did you experience a childhood?",
              options: {
                "Yes": { text: "To be a kid again...", end: "nostalgia" },
                "No": { text: "Why are you lying? It's bad.", restart: true }
              }
            },
            "No": { text: "I know how it feels.", restart: true },
            "I don't know": {
              question: "Are you a biological being?",
              options: {
                "Yes": { text: "This is you (+pictures)", end: "self" },
                "No": { text: "Why are you lying? It's bad.", restart: true }
              }
            }
          }
        },
        "No": {
          question: "Are you God?",
          options: {
            "Yes": { text: "Wrong. I am God.", restart: true },
            "No": {
              question: "Are you real?",
              options: {
                "Yes": { text: "You don’t have to stay", restart: true },
                "No": { text: "You don’t belong here.", restart: true },
                "I don't know": {
                  question: "Are you scared?",
                  options: {
                    "Yes": {
                      question: "Of what?",
                      options: {
                        "Unknown": { text: "Well then, you’re definitely a human being.", end: "end" },
                        "Humanity": { text: "Well then, you’re definitely a human being.", end: "end" },
                        "Life": { text: "Well then, you’re definitely a human being.", end: "end" },
                        "Everything": { text: "Well then, you’re definitely a human being.", end: "end" }
                      }
                    },
                    "No": { text: "Oh! Well, good for you :)", end: "end" }
                  }
                }
              }
            }
          }
        }
      }
    };

    const qEl = document.getElementById('question');
    const cEl = document.getElementById('choices');
    const backHome = document.getElementById('backHome');

    function showQuestion(node) {
      cEl.innerHTML = "";
      if (node.text) {
        qEl.textContent = node.text;
        if (node.restart) {
          const btn = document.createElement("button");
          btn.textContent = "Restart";
          btn.onclick = () => startQuiz();
          cEl.appendChild(btn);
        } else if (node.end) {
          const btn = document.createElement("button");
          btn.textContent = "End";
          btn.onclick = () => endQuiz();
          cEl.appendChild(btn);
        }
        return;
      }

      qEl.textContent = node.question;
      Object.keys(node.options).forEach(choice => {
        const btn = document.createElement("button");
        btn.textContent = choice;
        btn.onclick = () => showQuestion(node.options[choice]);
        cEl.appendChild(btn);
      });
    }

    function endQuiz() {
      qEl.textContent = "Thank you for playing.";
      cEl.innerHTML = "";
      backHome.classList.remove("hidden");
    }

    function startQuiz() {
      backHome.classList.add("hidden");
      showQuestion(quiz);
    }

    startQuiz();
  </script>
</body>
</html>
