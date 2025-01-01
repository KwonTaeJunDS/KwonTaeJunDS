<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200">
  <defs>
    <!-- 핑크색 글로우 효과를 위한 필터 -->
    <filter id="pink-glow" x="-50%" y="-50%" width="200%" height="200%">
      <feFlood flood-color="#ff69b4" result="flood"/>
      <feComposite in="flood" operator="in" in2="SourceAlpha" result="mask"/>
      <feGaussianBlur in="mask" stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <!-- 퍼플색 글로우 효과를 위한 필터 -->
    <filter id="purple-glow" x="-50%" y="-50%" width="200%" height="200%">
      <feFlood flood-color="#8a2be2" result="flood"/>
      <feComposite in="flood" operator="in" in2="SourceAlpha" result="mask"/>
      <feGaussianBlur in="mask" stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Welcome to -->
  <text x="50%" y="40%" text-anchor="middle" font-family="Arial Black" font-size="48" fill="#ff69b4" filter="url(#pink-glow)" style="text-shadow: 2px 2px #000;">
    Welcome to
  </text>
  
  <!-- Dami's Github -->
  <text x="50%" y="70%" text-anchor="middle" font-family="Arial Black" font-size="52" fill="#8a2be2" filter="url(#purple-glow)" style="text-shadow: 2px 2px #000;">
    Dami's Github
  </text>
  
  <!-- 노란색 테두리 효과 -->
  <text x="50%" y="40%" text-anchor="middle" font-family="Arial Black" font-size="48" fill="none" stroke="#ffff00" stroke-width="1">
    Welcome to
  </text>
  <text x="50%" y="70%" text-anchor="middle" font-family="Arial Black" font-size="52" fill="none" stroke="#ffff00" stroke-width="1">
    TaeJun's Github
  </text>
</svg>
-
Hello, I'm TaeJun Kwon.

I am a master's student at Kyungpook National University's Graduate School of Data Science.

I'm interested in **Deep Learning**, and **Computer Vision**.
-



<!--
**KwonTaeJunDS/KwonTaeJunDS** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
