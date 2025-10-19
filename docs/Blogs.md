<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Yaparla Bhargavi | Blog</title>
  <style>
    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      background: #f7f7f7;
      margin: 0;
      padding: 0;
    }
    .header {
      background: #23272b;
      color: #fff;
      padding: 30px 0 12px 0;
      text-align: center;
      border-bottom: 3px solid #338ccb;
    }
    .header-title {
      font-size: 2.25rem;
      font-weight: 900;
      letter-spacing: 1px;
      margin-bottom: 7px;
    }
    .header-desc {
      font-size: 1.13rem;
      color: #d3d6d9;
    }
    .container {
      display: flex;
      max-width: 1180px;
      margin: 35px auto 0 auto;
      padding: 0 18px;
      gap: 28px;
    }
    .main {
      flex: 2.8;
    }
    .sidebar {
      flex: 1.2;
      background: #eaf2f8;
      border-radius: 12px;
      box-shadow: 0 2px 12px #b0b8c055;
      padding: 1.7rem 1.1rem 1.15rem 1.1rem;
      max-width: 320px;
      min-width: 230px;
      margin-top: 0.8rem;
      height: fit-content;
    }
    .sidebar-title {
      font-size: 1.13rem;
      font-weight: 700;
      color: #235472;
      margin-bottom: 0.7rem;
      margin-top: 0.5rem;
    }
    .sidebar-text {
      font-size: 1.02rem;
      color: #222;
      margin-bottom: 1.18rem;
      line-height: 1.54;
    }
    .sidebar-connect a {
      color: #338ccb;
      text-decoration: none;
      margin-right: 7px;
      font-size: 1.01rem;
    }
    .sidebar-connect a:hover { text-decoration: underline; }
    .sidebar-img {
      width: 82px;
      display: block;
      margin: 0 auto 8px auto;
      border-radius: 9px;
      box-shadow: 0 2px 5px #aaa2;
    }
    .blog-post {
      background: #fff;
      border-radius: 10px;
      padding: 18px 24px 20px 24px;
      margin-bottom: 26px;
      box-shadow: 0 2px 8px #e0e4e855;
    }
    .blog-post-title {
      font-size: 1.15rem;
      font-weight: 700;
      color: #2b4765;
      margin-bottom: 0.38rem;
      text-decoration: none;
      display: inline-block;
    }
    .blog-meta {
      font-size: 0.98rem;
      color: #7a7f89;
      font-style: italic;
      margin-bottom: 0.9rem;
    }
    .blog-summary {
      font-size: 1.06rem;
      color: #222;
      line-height: 1.65;
    }
    @media (max-width: 940px) {
      .container { flex-direction: column; }
      .sidebar { max-width: 100%; margin: 1.6rem 0; }
      .main { max-width: 100%; }
      .blog-post { padding: 14px 12px; }
    }
  </style>
</head>
<body>
  <div class="header">
    <div class="header-title">Yaparla Bhargavi | Blog</div>
    <div class="header-desc">Aspiring Data Story Teller & Developer - Career, Projects, and Learning</div>
  </div>
  <div class="container">
    <div class="main">
      <div class="blog-post">
        <span class="blog-post-title">My Journey at FOSS United 2025</span>
        <div class="blog-meta">Event Reflection &mdash; Bangalore &mdash; September 29, 2025</div>
        <div class="blog-summary">
          Sharing the highlights and community lessons from attending FOSS United 2025. Open source, collaboration, and inspiration for student techies.
        </div>
      </div>
      <div class="blog-post">
        <span class="blog-post-title">Easy Guide to Prompt Engineering</span>
        <div class="blog-meta">AI &mdash; August 24, 2025</div>
        <div class="blog-summary">
          Tips and steps for mastering prompt engineering, from building great queries to optimizing output for real-world machine learning projects.
        </div>
      </div>
      <div class="blog-post">
        <span class="blog-post-title">Teachable Machine: No-Code AI Creativity</span>
        <div class="blog-meta">ML Experiments &mdash; June 20, 2025</div>
        <div class="blog-summary">
          Learning how to build and teach machine learning models without programming, and how students can use these tools in creative projects.
        </div>
      </div>
      <div class="blog-post">
        <span class="blog-post-title">LinkedIn Is Evolving — And So Should We</span>
        <div class="blog-meta">Career &mdash; June 18, 2025</div>
        <div class="blog-summary">
          Why professional storytelling matters on LinkedIn, and strategies for standing out by sharing impactful experiences and lessons.
        </div>
      </div>
      <div class="blog-post">
        <span class="blog-post-title">Tiger Analytics: Practical AI for Business</span>
        <div class="blog-meta">Conference Insights &mdash; May 18, 2025</div>
        <div class="blog-summary">
          Takeaways from PyConf Hyderabad: learning how Tiger Analytics applies machine learning for smarter business decisions.
        </div>
      </div>
    </div>
    <div class="sidebar">
      <div class="sidebar-title">About the Author</div>
      <div class="sidebar-text">
        Yaparla Bhargavi is a Data Science student, web developer, aspiring storyteller from Andhra Pradesh. She loves writing about data, technology, career skills, and sharing lessons with her peers.
      </div>
      <div class="sidebar-title">Connect</div>
      <div class="sidebar-connect">
        <a href="https://medium.com/@yaparlabhargavi" target="_blank">Medium</a>
        <a href="https://github.com/YaparlaBhargavi" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/in/bhargaviyaparla/" target="_blank">LinkedIn</a>
      </div>
    </div>
  </div>
</body>
</html>
