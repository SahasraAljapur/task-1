# task-1
main flow services task-1
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #460000;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        nav {
            background-color: #2b0101;
            text-align: center;
            padding: 0.5rem 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        .content {
            padding: 2rem;
            text-align: center;
        }

        footer {
            background-color: #460000;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 768px) {
            nav {
                display: flex;
                flex-direction: column;
                align-items: center;
            }

            nav a {
                margin: 10px 0;
            }
        }
    </style>
</head>

<body>
    <header>
        <h1>Landing Page</h1>
		<h2>Welcome to our Simple Landing page</h2>
		<p>take quizzes below and check your Knowledge:)</p>
    </header>
    <nav>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSfXJR4ACmVha7lQWuUAsOUcvtsDTsrSHb0vZ7X6wywXx61f7g/viewform?usp=sf_link">Math Quiz</a>
        <a href="https://forms.gle/pziLDg39cgNjCsZ27">Technology Quiz</a>
        <a href="https://forms.gle/VQe85a27mzs2yz6B9">General Knowledge Quiz</a>
    </nav>
    <div class="content">
        
        <p>This is a landing page created using HTML and CSS. It is responsive and works well on both desktop and mobile devices.</p>
    </div>
    <footer>
        <p>This page is created by Sahasra Aljapur to complete the task(1) given by Main Flow Services and Technologies.</p>
    </footer>
</body>

</html>
