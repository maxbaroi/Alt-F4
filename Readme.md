<article class="panel">
	<h2>Introduction to Alt-F4</h2>
	<div class="panel-inset-lighter mt0">
  	<p>Also known as Alt-F4, this is a weekly follow-on to Factorio's developer blog, the Factorio Friday Facts. It is written and edited entirely by the community, and aims to highlight various creations by the community, be it art, mods, gameplay, or anything else.</p>
		<ul>
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
	</div>
</article>

