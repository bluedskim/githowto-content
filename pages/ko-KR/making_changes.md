---
view: page
title: "5. 변경하기"
---

<h3>Goals</h3>

<ul><li>To learn to monitor the working directory’s state 작업폴더의 상태를 모니터링 하는 방법을 배운다</li></ul>

<h2><em>01</em> Changing the “Hello, World” page “Hello, World” 페이지 변경</h2>

<p>Let&#8217;s add some HTML-tags to our greeting. Change the file contents to: 우리의 인사말에 HTML태그를 추가하자. 이 파일의 내용을 아래와 같이 변경한다:</p>

<h4 class="h4-pre">파일: <em>hello.html</em></h4>

<pre class="file"><strong>&lt;h1&gt;</strong>Hello, World!<strong>&lt;/h1&gt;</strong></pre>

<h2><em>02</em> Checking the status 상태 확인</h2>

<p>Check the working directory’s status. 작업 폴더의 상태를 확인한다.</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git status</pre>

<p>결과는 &#8230;</p>

<h4 class="h4-pre">결과:</h4>

<pre class="sample">$ git status
# On branch master
# Changes not staged for commit:
#   (use "git add &lt;file&gt;..." to update what will be committed)
#   (use "git checkout -- &lt;file&gt;..." to discard changes in working directory)
#
#	modified:   hello.html
#
no changes added to commit (use "git add" and/or "git commit -a")</pre>

<p>The first important aspect here is that git knows <code>hello.html</code> file has been changed, but these changes are not yet committed to the repository. 결과에서 중요한 것은 git은 <code>hello.html</code> 파일이 변경되었다는 것과 이 파일이 저장소에 커밋되지 않았다는 것을 알고 있다는 점이다.</p>

<p>Another aspect is that the status message hints about what to do next. 그리고 주목해야 할 것은 결과 메시지를 통해 다음에 해야할 작업을 알 수 있다는 것이다. If you want to add these changes to the repository, use <code>git add</code>. To undo the changes use <code>git checkout</code>. 이 변경사항을 저장소에 추가하려 한다면 <code>git add</code> 명령을 실행한다. 변경을 취소하려 한다면 <code>git checkout</code>을 실행한다.</p>

<h2><em>03</em> 다음 주제 ...</h2>

<p>Staging the changes. 변경사항을 반영하기</p>
