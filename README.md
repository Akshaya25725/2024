# 2024
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2024 Reflection Questionnaire</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #5c67f2;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #5c67f2;
        }
        label {
            display: block;
            margin: 15px 0 5px;
            font-weight: bold;
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #5c67f2;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #4b56c2;
        }
    </style>
</head>
<body>
    <header>
        <h1>2024 Reflection Questionnaire</h1>
        <p>Let’s reflect on your journey as a 19-year-old medical student.</p>
    </header>
    <div class="container">
        <form action="#" method="POST">
            <h2>About You</h2>
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            
            <label for="location">Where are you studying?</label>
            <input type="text" id="location" name="location" placeholder="City/College name" required>
            
            <label for="word">If you had to describe yourself in one word, what would it be?</label>
            <input type="text" id="word" name="word" placeholder="E.g., Resilient, Dreamer">
            
            <label for="memory">What’s the first memory of 2024 that comes to mind?</label>
            <textarea id="memory" name="memory" placeholder="Describe your memory here..." rows="4"></textarea>

            <h2>Your Life in Medicine</h2>
            <label for="moment">What was your biggest “aha!” moment in medicine this year?</label>
            <textarea id="moment" name="moment" placeholder="Share your story..." rows="4"></textarea>
            
            <label for="challenge">What was your biggest academic challenge in 2024?</label>
            <textarea id="challenge" name="challenge" placeholder="Explain how you tackled it..." rows="4"></textarea>
            
            <label for="motivation">What kept you going on tough days?</label>
            <textarea id="motivation" name="motivation" placeholder="E.g., Family, passion, mentors..." rows="4"></textarea>

            <h2>Looking Ahead</h2>
            <label for="goal">What’s one goal or dream you’re excited about for 2025?</label>
            <textarea id="goal" name="goal" placeholder="Write your dream here..." rows="4"></textarea>

            <button type="submit">Submit Your Reflection</button>
        </form>
    </div>
</body>
</html>
