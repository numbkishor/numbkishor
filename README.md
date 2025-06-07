<!-- Load Google Fonts for futuristic look -->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700;900&family=Audiowide&family=Share+Tech+Mono&display=swap" rel="stylesheet" />

<!-- Container for entire README -->
<div style="
  font-family: 'Orbitron', 'Audiowide', 'Share Tech Mono', monospace;
  color: #00F0FF;
  background: #000011;
  padding: 30px 20px;
  border-radius: 20px;
  box-shadow:
    0 0 20px #00F0FF,
    inset 0 0 50px #00DFD8;
  max-width: 900px;
  margin: auto;
  user-select: none;
">

  <!-- Top Neon Wave Background -->
  <svg viewBox="0 0 500 150" preserveAspectRatio="none"
       style="width: 100%; height: 110px; margin-bottom: -60px; filter: drop-shadow(0 0 5px #00DFD8);">
    <path d="M0,60 C150,150 350,0 500,60 L500,150 L0,150 Z"
          fill="url(#grad1)" />
    <defs>
      <linearGradient id="grad1" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#00DFD8" />
        <stop offset="50%" stop-color="#007CF0" />
        <stop offset="100%" stop-color="#FFC300" />
      </linearGradient>
    </defs>
  </svg>

  <!-- Header -->
  <div style="text-align:center; margin-bottom: 40px;">
    <h1 style="
      font-size: 4.8rem;
      font-weight: 900;
      background: linear-gradient(270deg, #00DFD8, #007CF0, #FFC300, #00DFD8);
      background-size: 800% 800%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: neon-gradient 10s ease infinite;
      text-shadow:
        0 0 10px #00DFD8,
        0 0 30px #FFC300,
        0 0 40px #007CF0,
        0 0 50px #00DFD8;
      margin-bottom: 10px;
      font-family: 'Orbitron', sans-serif;
    ">
      Hi there 👋, I'm <span style="color:#FFC300;">Kishor</span>
    </h1>
    <h3 style="
      font-weight: 600;
      font-size: 1.5rem;
      letter-spacing: 0.08em;
      color: #00B3FF;
      text-shadow: 0 0 10px #00B3FF;
      font-family: 'Audiowide', cursive;
    ">
      A curious Computer Science student exploring the world of code
    </h3>

    <!-- Profile View Badge (white background to stand out) -->
    <div style="
      margin-top: 15px;
      display: inline-block;
      padding: 4px 14px;
      border-radius: 40px;
      font-family: 'Share Tech Mono', monospace;
      font-weight: 700;
      font-size: 1rem;
      color: #000;
      background: #FFC300;
      box-shadow:
        0 0 10px #FFC300,
        inset 0 0 8px #FFA500;
      user-select: none;
      cursor: default;
      transition: transform 0.3s ease;
    "
      onmouseover="this.style.transform='scale(1.15)';"
      onmouseout="this.style.transform='scale(1)';"
    >
      <img src="https://komarev.com/ghpvc/?username=numbkishor&label=Profile%20views&color=000000&style=flat-square" alt="Profile views" style="vertical-align:middle; margin-right:6px; height:20px;" />
      Profile Views
    </div>
  </div>

  <!-- Animated visitor badge -->
  <div style="text-align:center; margin: 15px 0 40px;">
    <img src="https://visitor-badge.laobi.icu/badge?page_id=numbkishor.numbkishor" alt="visitor badge" style="
      filter: drop-shadow(0 0 6px #00DFD8);
      animation: flicker 3s infinite alternate;
      user-select:none;
      cursor:pointer;
      max-width: 220px;
    " />
  </div>

  <hr style="border: none; height: 3px; border-radius: 2px; background: linear-gradient(90deg, #00DFD8, #007CF0, #FFC300); margin-bottom: 40px;" />

  <!-- Sections container -->
  <div style="display: flex; flex-wrap: wrap; gap: 50px; justify-content: center;">

    <!-- What I'm Learning -->
    <section style="flex: 1 1 300px; max-width: 400px; background: rgba(0,223,216,0.1); padding: 25px; border-radius: 15px; box-shadow: 0 0 20px #00DFD8;">
      <h2 style="
        font-family: 'Orbitron', sans-serif;
        font-weight: 700;
        font-size: 2rem;
        color: #FFC300;
        text-shadow: 0 0 12px #FFC300;
        margin-bottom: 15px;
      ">🌱 What I'm Learning</h2>
      <p style="
        font-size: 1.25rem;
        color: #00B3FF;
        font-weight: 600;
        letter-spacing: 0.04em;
        text-shadow: 0 0 8px #00B3FF;
      ">
        Currently mastering <span style="color:#FFC300; font-weight: 900;">C++</span> to write fast, clean, and efficient code.
      </p>
    </section>

    <!-- Projects & Work -->
    <section style="flex: 1 1 300px; max-width: 400px; background: rgba(0,223,216,0.1); padding: 25px; border-radius: 15px; box-shadow: 0 0 20px #00DFD8;">
      <h2 style="
        font-family: 'Orbitron', sans-serif;
        font-weight: 700;
        font-size: 2rem;
        color: #FFC300;
        text-shadow: 0 0 12px #FFC300;
        margin-bottom: 15px;
      ">💻 Projects & Work</h2>
      <p style="
        font-size: 1.25rem;
        color: #00B3FF;
        font-weight: 600;
        letter-spacing: 0.04em;
        text-shadow: 0 0 8px #00B3FF;
      ">
        Explore all my open source projects:<br />
        <a href="https://github.com/numbkishor?tab=repositories" target="_blank" style="
          color: #FFC300;
          text-decoration: none;
          font-weight: 900;
          text-shadow: 0 0 10px #FFC300;
          transition: color 0.3s ease;
        " onmouseover="this.style.color='#00DFD8'" onmouseout="this.style.color='#FFC300'">
          github.com/numbkishor?tab=repositories
        </a>
      </p>
    </section>

  </div>

  <!-- Contact -->
  <div style="text-align:center; margin: 60px 0;">
    <h2 style="
      font-family: 'Orbitron', sans-serif;
      font-weight: 700;
      font-size: 2rem;
      color: #FFC300;
      text-shadow: 0 0 12px #FFC300;
      margin-bottom: 25px;
    ">📫 How to Reach Me</h2>
    <a href="mailto:contact.kishrcreates@gmail.com" style="
      font-size: 1.4rem;
      font-weight: 700;
      color: #00DFD8;
      text-decoration: none;
      text-shadow: 0 0 10px #00DFD8;
      border: 2px solid #00DFD8;
      padding: 12px 25px;
      border-radius: 40px;
      transition: background 0.3s ease, color 0.3s ease;
      display: inline-block;
      cursor: pointer;
    " onmouseover="this.style.background='#00DFD8'; this.style.color='#000';" onmouseout="this.style.background='transparent'; this.style.color='#00DFD8';">
      contact.kishrcreates@gmail.com
    </a>
  </div>

  <!-- Social Links -->
  <div style="text-align:center; margin-bottom: 50px;">
    <h2 style="
      font-family: 'Orbitron', sans-serif;
      font-weight: 700;
      font-size: 2rem;
      color: #FFC300;
      text-shadow: 0 0 12px #FFC300;
      margin-bottom: 25px;
    ">🔗 Connect With Me</h2>

    <div style="display: inline-flex; gap: 30px;">

      <!-- Social Icon Template -->
      <a href="https://facebook.com/install.io" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #3b5998);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #3b5998;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #3b5998)';"
      >
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" width="36" />
      </a>

      <a href="https://instagram.com/kishhh__or" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #E1306C);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: radial-gradient(circle at 30% 30%, #FCAF45, #D6249F, #285AEB);
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #E1306C)';"
      >
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" width="36" />
      </a>

      <a href="https://www.codechef.com/users/kishor_15" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #CC4B00);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #CC4B00;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #CC4B00)';"
      >
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg" alt="CodeChef" width="36" />
      </a>

      <a href="https://www.hackerrank.com/kishorarbo18" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #2EC866);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #2EC866;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #2EC866)';"
      >
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="HackerRank" width="36" />
      </a>

      <a href="https://codeforces.com/profile/kishor_18" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #1F8FFF);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #1F8FFF;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #1F8FFF)';"
      >
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codeforces.svg" alt="Codeforces" width="36" />
      </a>

      <a href="https://leetcode.com/numbkishor/" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #FFA116);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #FFA116;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #FFA116)';"
      >
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leetcode.svg" alt="LeetCode" width="36" />
      </a>

      <a href="https://www.youtube.com/@kishor_arbo" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #FF0000);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #FF0000;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #FF0000)';"
      >
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="YouTube" width="36" />
      </a>

      <a href="https://www.linkedin.com/in/kishorarbo/" target="_blank" rel="noopener noreferrer"
         style="
           display: inline-block;
           filter: drop-shadow(0 0 8px #0A66C2);
           transition: transform 0.3s ease, filter 0.3s ease;
           border-radius: 50%;
           background: #0A66C2;
           padding: 10px;
         "
         onmouseover="this.style.transform='scale(1.2)'; this.style.filter='drop-shadow(0 0 15px #FFC300)';"
         onmouseout="this.style.transform='scale(1)'; this.style.filter='drop-shadow(0 0 8px #0A66C2)';"
      >
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linkedin.svg" alt="LinkedIn" width="36" />
      </a>

    </div>
  </div>

  <!-- GitHub Stats -->
  <div style="text-align:center; margin-bottom: 50px;">
    <h2 style="
      font-family: 'Orbitron', sans-serif;
      font-weight: 700;
      font-size: 2rem;
      color: #FFC300;
      text-shadow: 0 0 12px #FFC300;
      margin-bottom: 30px;
    ">📊 GitHub Stats</h2>

    <img src="https://github-readme-stats.vercel.app/api?username=numbkishor&show_icons=true&count_private=true&hide=prs&theme=transparent&bg_color=000011&icon_color=00DFD8&title_color=FFC300&text_color=00B3FF&hide_border=true" alt="GitHub Stats" style="max-width: 100%; border-radius: 20px; box-shadow: 0 0 30px #00DFD8;" />

    <div style="margin-top: 40px;">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=numbkishor&theme=dark&hide_border=true&stroke=FFC300&ring=00DFD8&fire=FFC300&currStreakNum=00B3FF&sideNums=FFC300" alt="GitHub Streak" style="max-width: 100%; border-radius: 20px; box-shadow: 0 0 30px #FFC300;" />
    </div>
  </div>

</div>

<!-- Animations -->
<style>
@keyframes neon-gradient {
  0%{background-position:0% 50%;}
  50%{background-position:100% 50%;}
  100%{background-position:0% 50%;}
}

@keyframes flicker {
  0%, 100% { opacity: 1; filter: drop-shadow(0 0 6px #00DFD8); }
  50% { opacity: 0.8; filter: drop-shadow(0 0 10px #00F0FF); }
}
</style>
