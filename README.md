<article class="markdown-body entry-content container-lg" itemprop="text">
  <h1>Ví dụ Dockerfile cơ bản</h1>
  <p>Use with Docker <a href="http://www.docker.io" rel="nofollow">http://www.docker.io</a></p>
  <p>To build an image with docker is pretty simple:</p>
  <pre>
    <code>docker run -i -t rethinkdb</code>
  </pre>
  
  <pre>
    <code>cd dockerfile</code>
  </pre>
  <p>Then to run that image and attach to it at the same time:</p>
  <pre><code>docker run -i -t rethinkdb
  </code></pre>
  <p>Or to run it in the background</p>
  <pre><code>docker run -d rethinkdb
  </code></pre>
</article>
