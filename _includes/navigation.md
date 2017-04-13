<h1>
  <a href="/">ANDREW BRADDOCK</a>
</h1>

{% assign current_page = page.path | split:"." | first%}

<ul>
  <li>
    <a {% if current_page == 'work' %}class="active"{%endif%} href="/work">"AAAA"</a>
  </li>
  <li>
    <a {% if current_page == 'about' %}class="active"{%endif%} href="/about">"BBBB"</a>
  </li>
  <li>
    <a href="/scoot">"DDDD"</a>
  </li>
</ul>
