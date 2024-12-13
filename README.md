<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E2 COMPUTER LAB EXERCISE</title>
    <style>
        body {
            background-color: #006400; /* Dark green background */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: white;
        }
        header {
            background-color: #228B22; /* Lighter green for header */
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #ffcc00;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
        }
        header h1 {
            color: white;
            margin: 0;
            font-size: 30px;
            font-weight: bold; /* Bold text */
            text-transform: uppercase; /* All caps */
        }
        header h2 {
            color: white;
            margin: 10px 0;
            font-size: 20px;
            font-weight: normal;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .introduction {
            margin: 20px;
            padding: 20px;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            color: black;
        }
        .container {
            margin: 20px;
            padding: 20px;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            color: black;
        }
        .blog-section {
            margin-bottom: 30px;
        }
        .decorative-line {
            height: 4px;
            background: linear-gradient(to right, #ffcc00, #ff6600);
            margin: 20px 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #228B22;
        }
        th, td {
            padding: 10px;
            text-align: center;
            background-color: #e6f0ff;
            color: black;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form select, form textarea, form button {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #228B22;
            border-radius: 5px;
        }
        .image-container img {
            width: 100%;
            height: auto;
            border: 2px solid #228B22;
            margin-bottom: 10px;
        }
        iframe, audio {
            width: 100%;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>E2 COMPUTER LAB EXERCISE</h1>
        <h2>PAULO DESTAJO</h2> <!-- Added name here -->
        <nav>
            <a href="#">Home</a>
            <a href="#">Article</a>
            <a href="#">Blog</a>
            <a href="#">Form</a>
        </nav>
    </header>
    <!-- Introduction Section -->
    <div class="introduction">
        <h2>Welcome to Our Web Page!</h2> <!-- Changed text -->
    </div>
    <div class="container">
        <!-- Blog Section -->
        <div class="blog-section">
            <h2>Understanding Malware, Viruses, Spam, and Antiviruses</h2>
            <p>Malware, viruses, and spam are serious threats to technology and personal data. Malware refers to malicious software designed to harm devices, steal information, or spy on users. Viruses are a subset of malware that spread from one system to another, often via infected files. Spam refers to unsolicited messages, often promoting scams or harmful links.</p>
            <h3>What is Malware?</h3>
            <p>Malware is a broad term that encompasses any kind of malicious software, including viruses, worms, ransomware, spyware, and Trojan horses. It can cause significant damage by corrupting data, stealing personal information, and disrupting the performance of systems.</p>
            <h3>What is a Virus?</h3>
            <p>A virus is a type of malware that attaches itself to a legitimate program or file, and once executed, it spreads by replicating itself. Viruses can cause system slowdowns, file corruption, and data loss.</p>
            <h3>What is Spam?</h3>
            <p>Spam refers to unsolicited, often irrelevant or inappropriate messages sent over the internet, usually for the purpose of advertising or spreading malware. It can appear in the form of emails, social media posts, or text messages.</p>
            <h3>What is Antivirus Software?</h3>
            <p>Antivirus software is designed to detect and remove malware from a computer or network. It works by scanning files for known malware signatures or by detecting abnormal behavior that indicates malicious activity.</p>
            <div class="decorative-line"></div>
        </div>
        <div class="blog-section">
            <h2>Plagiarism and its Consequences</h2>
            <p>Plagiarism is the unethical act of using someone else's work without proper citation or permission. It is a violation of intellectual property rights and can lead to serious consequences in both academic and professional settings.</p>        
            <h3>Reported Cases of Plagiarism:</h3>
            <table>
                <thead>
                    <tr>
                        <th>Case</th>
                        <th>Country</th>
                        <th>Punishment</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Academic Plagiarism</td>
                        <td>USA</td>
                        <td>Expulsion from institution</td>
                    </tr>
                    <tr>
                        <td>Copyright Violation</td>
                        <td>India</td>
                        <td>Fines and imprisonment</td>
                    </tr>
                    <tr>
                        <td>Plagiarized Article</td>
                        <td>UK</td>
                        <td>Public apology and lawsuit</td>
                    </tr>
                </tbody>
            </table>
            <h3>Nature of Punishments in Different Countries</h3>
            <p>The nature and severity of plagiarism punishments vary depending on the country and the severity of the offense. In the USA, academic plagiarism can result in expulsion, while in countries like India and the UK, there can be legal actions such as fines, imprisonment, or lawsuits. The focus is on protecting intellectual property and maintaining academic integrity.</p>
            <div class="decorative-line"></div>
        </div>
        <!-- Embedded Media -->
        <div class="image-container">
            <img src="your-image-url-here.jpg" alt="Sample Image">
        </div>
        <!-- Changed YouTube video -->
        <iframe width="100%" height="400" src="https://www.youtube.com/embed/Ip-u5NZJiwY" title="YouTube video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
            Your browser does not support the audio tag.
        </audio>
        <!-- Form Section -->
        <h2>Contact Form</h2>
        <form action="submit-form.php" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="feedback">Feedback:</label>
            <textarea id="feedback" name="feedback" rows="4" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
