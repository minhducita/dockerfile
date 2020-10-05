<article class="markdown-body entry-content container-lg" itemprop="text">
  <h1>Ví dụ Dockerfile cơ bản</h1>
  <p>Tham khảo cách tạo Dockerfile tại <a href="https://viblo.asia/p/docker-tao-docker-images-tu-dockerfile-3P0lPORvZox" rel="nofollow">https://viblo.asia/p/docker-tao-docker-images-tu-dockerfile-3P0lPORvZox</a></p>
  <p>Bước 1. Bạn vào thư mục chứa Dockerfile bằng lệnh sau</p>
  <pre><code>cd dockerfile</code></pre>
  <p>Bước 2. Build Docker image và tạo container mới trên image vừa tạo</p>
  <pre><code>docker build -t nginx_image .</code></pre>
  <p>Bước 3. Chạy lệnh sau để tạo container mới từ nginx_image ở trên:</p>
  <pre><code>docker run -d -v /webroot:/var/www/html -p 9000:80 --name viblo_test nginx_image</code></pre>


  <p>Or to run it in the background</p>
  <pre><code>docker run -d rethinkdb
  </code></pre>
</article>
