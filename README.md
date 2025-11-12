<!-- Создайте файл index.html со следующим содержимым -->
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Тест: Основы алгоритмов и программирования</title>
    <style>
        /* ВСТАВЬТЕ ВЕСЬ CSS-КОД ЗДЕСЬ */
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); min-height: 100vh; padding: 20px; }
        /* ... остальной CSS код ... */
    </style>
</head>
<body>
    <div class="container">
        <!-- ВСТАВЬТЕ ВЕСЬ HTML-КОД ТЕСТА ЗДЕСЬ -->
        <div class="header">
            <h1>🧠 Тест по алгоритмам и программированию</h1>
            <p>Проверьте свои знания основ программирования</p>
        </div>
        
        <div class="test-content">
            <form id="quizForm">
                <!-- Все 10 вопросов -->
                <!-- Вопрос 1 -->
                <div class="question" id="q1">
                    <div class="question-number">Вопрос 1/10</div>
                    <p>Что такое алгоритм в программировании?</p>
                    <div class="options">
                        <label class="option"><input type="radio" name="q1" value="a"> Язык программирования</label>
                        <label class="option"><input type="radio" name="q1" value="b"> Точная последовательность действий для решения задачи</label>
                        <label class="option"><input type="radio" name="q1" value="c"> Тип данных в Python</label>
                        <label class="option"><input type="radio" name="q1" value="d"> Математическая формула</label>
                    </div>
                    <div class="explanation" id="exp1"></div>
                </div>
                <!-- ... остальные вопросы ... -->
            </form>
            <div id="finalResult" class="result"></div>
        </div>
    </div>

    <script>
        // ВСТАВЬТЕ ВЕСЬ JavaScript-КОД ЗДЕСЬ
        const correctAnswers = {
            q1: { answer: "b", explanation: "✅ <strong>Правильно!</strong> Алгоритм - это точная последовательность действий..." },
            // ... все остальные ответы ...
        };

        function checkAnswers() {
            // ... вся функция проверки ...
        }
        // ... остальные функции ...
    </script>
</body>
</html>
