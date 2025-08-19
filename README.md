# June
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Junehyeok Yoon</title>
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <style>
        body {
            background: #f3f3f3;
            font-family: 'Noto Sans KR', 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #222;
        }
        header {
            width: 100%;
            background: linear-gradient(90deg, #1976d2 70%, #64b5f6 100%);
            color: #fff;
            padding: 48px 0 32px 0;
            text-align: center;
        }
        .profile-img {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 2px 10px rgba(0,0,0,0.09);
            border: 4px solid #fff;
            margin-bottom: 18px;
        }
        h1 {
            font-size: 2.6rem;
            font-weight: 700;
            margin-bottom: 10px;
            margin-top: 0;
        }
        .intro {
            font-size: 1.25rem;
            color: #e3f2fd;
            margin-bottom: 18px;
        }
        nav.links {
            margin-top: 22px;
        }
        nav.links a {
            display: inline-block;
            margin: 0 14px;
            padding: 9px 22px;
            border-radius: 22px;
            background: #fff;
            color: #1976d2;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.07rem;
            box-shadow: 0 1px 6px rgba(25, 118, 210, 0.09);
            transition: background .2s, color .2s;
        }
        nav.links a:hover {
            background: #1976d2;
            color: #fff;
        }

        .main-section {
            max-width: 900px;
            margin: 36px auto 0 auto;
            padding: 0 18px;
        }
        .section-title {
            font-size: 1.35rem;
            font-weight: 700;
            color: #1976d2;
            margin: 40px 0 16px 0;
            text-align: left;
        }
        .section {
            background: #fff;
            border-radius: 16px;
            box-shadow: 0 3px 16px rgba(0,0,0,0.06);
            margin-bottom: 44px;
            padding: 30px 28px 20px 28px;
            text-align: left;
        }
        .section ul {
            padding-left: 1.1em;
            font-size: 1.08rem;
            margin: 0;
        }
        .section li {
            margin-bottom: 7px;
        }
        @media (max-width: 700px) {
            .main-section { padding: 0 4px; }
            header { padding: 36px 0 24px 0; }
            .section { padding: 18px 10px 10px 10px; }
            h1 { font-size: 2rem; }
            .profile-img { width: 90px; height: 90px; }
        }
    </style>
</head>
<body>
    <header>
        <img src="profile.png" class="profile-img" alt="Profile Photo">
        <h1>Junehyeok Yoon</h1>
        <div class="intro">
            Software Engineer & AI Researcher<br>
            Interested in deep learning, web, and open source.<br>
            📍 Seoul, South Korea
        </div>
        <nav class="links">
            <a href="https://github.com/junehyeokyoon" target="_blank">GitHub</a>
            <a href="mailto:junehyeokyoon@gmail.com">Email</a>
            <a href="https://www.linkedin.com/in/junehyeokyoon/" target="_blank">LinkedIn</a>
        </nav>
    </header>
    <div class="main-section">
        <div class="section">
            <div class="section-title">Education</div>
            <ul>
                <li>B.S. in Computer Science, Seoul National University (2022 - Present)</li>
                <li>Relevant Coursework: Machine Learning, Algorithms, Data Structures</li>
                <!-- 추가/수정 가능 -->
            </ul>
        </div>
        <div class="section">
            <div class="section-title">Publication</div>
            <ul>
                <li>Yoon, J., et al. "Deep Neural Networks for Korean Speech Recognition." <i>Korea AI Conference</i>, 2024.</li>
                <li>Yoon, J., et al. "Web-Based AI Applications: Trends and Challenges." <i>Journal of Web Engineering</i>, 2023.</li>
                <!-- 실제 논문/발표로 교체 가능 -->
            </ul>
        </div>
        <div class="section">
            <div class="section-title">Research Interests</div>
            <ul>
                <li>Deep Learning & Neural Networks</li>
                <li>Natural Language Processing (NLP)</li>
                <li>Web Development & Open Source</li>
                <!-- 관심 분야 추가/수정 가능 -->
            </ul>
        </div>
        <div class="section">
            <div class="section-title">Awards</div>
            <ul>
                <li>ACM ICPC Regional Finalist (2023)</li>
                <li>Samsung Software Challenge Winner (2022)</li>
                <li>Best Paper Award, Korea AI Conference (2021)</li>
                <!-- 수상 경력 추가/수정 가능 -->
            </ul>
        </div>
    </div>
</body>
</html>
