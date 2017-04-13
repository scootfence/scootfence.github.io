<h1>
  <a href="/">ANDREW BRADDOCK</a>
</h1>

{% assign current_page = page.path | split:"." | first%}

<ul>
  <li>
    <a {% if current_page == 'work' %}class="active"{%endif%} href="/work">"ANDY"</a>
  </li>
  <li>
    <a {% if current_page == 'about' %}class="active"{%endif%} href="/about">"AANDYY"</a>
  </li>
  <li>
    <a href="/scoot">"AAANDYYY"</a>
  </li>
</ul>
