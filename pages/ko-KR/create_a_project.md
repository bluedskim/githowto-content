---
view: page
title: "3. 프로젝트 만들기"
---

<h3>목표</h3>

<ul><li>초기 상태에서 git 저장소를 만드는  법을 배운다.</li></ul>

<h2><em>01</em> “Hello, World!” html 페이지 만들기</h2>

<p>비어있는 작업 폴더에(튜토리얼 자료를 다운 받았다면  work 폴더) hello라는 폴더를 만들고 그 안에 hello.html파일을 만들어 아래의 내용을 넣는다.</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">mkdir hello
cd hello
touch hello.html</pre>

<h4 class="h4-pre">파일
: <em>hello.html</em></h4>

<pre class="file">Hello, World!</pre>

<h2><em>02</em> 저장소 만들기</h2>

<p>이제 파일을 하나 가지고 있는 폴더가 준비되었다. 이 디렉토리에 저장소를 만들기 위해 <code>git init</code> 를 실행한다.</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git init</pre>

<h4 class="h4-pre">결과:</h4>

<pre class="sample">$ git init
Initialized empty Git repository in /Users/alex/Documents/Presentations/githowto/auto/hello/.git/
</pre>

<h2><em>03</em> 만든 페이지를 저장소에 추가</h2>

<p>이제 “Hello, World” 페이지를 저장소에 추가하자.</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git add hello.html
git commit -m "First Commit"</pre>

<p>결과는 &#8230;</p>

<h4 class="h4-pre">결과:</h4>

<pre class="sample">$ git add hello.html
$ git commit -m "First Commit"
[master (root-commit) 911e8c9] First Commit
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 hello.html</pre>
