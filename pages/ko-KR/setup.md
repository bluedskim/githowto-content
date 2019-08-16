---
view: page
title: "1. 준비"
---

<h3>목표</h3>

<ul><li>Git을 사용하기 위한 준비를 완벽하게 한다</li></ul>

<h2><em>01</em> 이름과 이메일 주소 설정</h2>

<p>Git을 처음 써본다면 먼저 이름과 이메일을 설정해야 한다. 당신의 이름과 이메일을 가지고 아래의 명령을 수행해서 Git이 당신을 인식할 수 있도록 한다. 이미 이름과 이메일을 설정했다면 2번으로 넘어간다.</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git config --global user.name "이름"
git config --global user.email "이메일@whatever.com"</pre>

<h2><em>02</em> OS별로 개행문자 세팅하기</h2>

<p>Unix 혹은 Mac:</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git config --global core.autocrlf input
git config --global core.safecrlf true</pre>

<p>윈도우즈</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git config --global core.autocrlf true
git config --global core.safecrlf true</pre>
