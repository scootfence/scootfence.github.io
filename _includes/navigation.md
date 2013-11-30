<h1>
  <a href="/">ANDREW BRADDOCK</a>
</h1>

{% assign current_page = page.path | split:"." | first%}

<ul>
  <li>
    <a {% if current_page == 'work' %}class="active"{%endif%} href="/work">WORK</a>
  </li>
  <li>
    <a {% if current_page == 'about' %}class="active"{%endif%} href="/about">ABOUT</a>
  </li>
  <li>
    <a href="/scoot">SCOOT</a>
  </li>
</ul>