<head>
    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
        crossorigin="anonymous"
        referrerpolicy="no-referrer"
    />
    <link rel="stylesheet" href="assets/css/style.css">
</head>

<body>
    <header class="site-header">
        <div class="header-container">
        <a href="{{ "/" | relative_url }}">{{ site.title }}</a>
        <nav class="site-nav">
            <a href="{{ "/#about"        | relative_url }}">About</a>
            <a href="{{ "/#publications" | relative_url }}">Publications</a>
            <a href="{{ "assets/resume/Jaeyoung_Kang_Resume.pdf" | relative_url }}" target="_blank">Resume</a>
        </nav>
        </div>
    </header>
    <div class="profile-container">
        <!-- LEFT COLUMN -->
        <div class="profile-sidebar">
            <img src="assets/img/profile_pic.jpg" alt="Jaeyoung Kang">
            <h2>Jaeyoung Kang</h2>
            <p>Ph.D. Candidate & Research Assistant</p>
            <ul>
                <li>
                    <span class="icon">📍</span>
                    <span class="label">Champaign, IL, USA</span>
                </li>
                <li>
                    <span class="icon">🏫</span>
                    <span class="label">ECE @ UIUC</span>
                </li>
                <li>
                    <span class="icon">✉️</span>
                    <span class="label"><a href="mailto:jaeyoung@illinois.edu">Email</a></span>
                </li>
                <li>
                    <span class="icon">🔗</span>
                    <span class="label"><a href="https://fast.ece.illinois.edu/">FAST Lab</a></span>
                </li>
                <li>
                    <span class="icon"><i class="fab fa-github"></i></span>
                    <span class="label"><a href="https://github.com/Jae0504" target="_blank">GitHub</a></span>
                </li>
                <li>
                    <span class="icon"><i class="fab fa-linkedin"></i></span>
                    <span class="label"><a href="https://www.linkedin.com/in/jaeyoung-kang-653aa8250/" target="_blank">LinkedIn</a></span>
                </li>
            </ul>
        </div>
        <!-- RIGHT COLUMN -->
        <div class="profile-main">
            <section id="about">
            <h1>About</h1>
            <p>Hi, I am <strong>Jaeyoung Kang</strong>, a 2nd-year Ph.D. candidate in Electrical & Computer Engineering at UIUC, and a member of the <a href="https://fast.ece.illinois.edu/">FAST Lab</a> led by Professor Nam Sung Kim.</p>
            <p>I am interested in accelerator systems and datacenters. I completed my undergraduate ECE degree at UIUC in December 2023 and joined graduate school in January 2024.</p>
            </section>
            <hr class="divider"/>
            <section id="publications">
            <h1>Publications</h1>
            <ul class="pub-list">
                <li><a href="…">Paper Title One</a><br/>
                    <small>J. Kang, et al., Conference 2024</small>
                </li>
                <li><a href="…">Paper Title Two</a><br/>
                    <small>J. Kang, et al., Journal 2023</small>
                </li>
            </ul>
            </section>
        </div>
    </div>
</body>