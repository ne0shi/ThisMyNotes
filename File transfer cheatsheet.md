<p>File transfer skills in the red team post penetration test
Author: xax007 @ know Chuangyu 404 ScanV security service team of the blog:<br>
https://xax007.github.io/ (https://xax007.github.io/)</br>
</p>
<h2>Build an HTTP server</h2>
<h3> Python</h3>
<h2>python2:</h2>
<pre><p>python -m SimpleHTTPServer 1337</p></pre>
<h2>python3:</h2>
<p>python -m http.server 1337</p>
<h2>PHP 5.4+:</h2>
<pre><p>When the PHP version is greater than 5.4, you can use PHP to start the HTTP service in the current directory, the port is 1337.
<p>php -S 0.0.0.:1337</p></pre>
<h2> Ruby:  </h2>
<pre><p> The following command will start the HTTP Service in the current directory, the port is 1337.
<p>ruby -rwebrick -e'WEBrick::HTTPServer.new(:Port => 1337, :DocumentRoot => Dir.pwd </p> </pre>
<h2>Ruby.19.2+: </h2>
<pre><p>ruby -run -e httpd . -p 1337</p></pre>
<h2>Perl: </h2>
<pre><p>perl-MHTTP::Server::Brick-e'$s=HTTP::Server::Brick->new(port=>1337); $s->mountperl-MIO::All-e'io(":8080")->fork->accept->(sub { $_[0] < io(-x $1 +? "./$1 |" <p></pre>

<h1>more information in : <link>https://www.exploit-db.com/docs/46515</link>
