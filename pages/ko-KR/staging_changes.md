---
view: page
title: "6. Staging the changes 변경사항을 추가하기"
---

<h3>목표</h3>

<ul><li>To learn to stage changes for the upcoming commits 커밋을 하기 전에 변경사항을 추가(adding, staging)하는 방법을 배운다</li></ul>

<h2><em>01</em> Adding changes</h2>

<p>Now command git to stage changes. 변경 사항을 추가하고 Check the status 상태를 확인해보자</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git add hello.html
git status</pre>

<p>결과는 &#8230;</p>

<h4 class="h4-pre">결과:</h4>

<pre class="sample">$ git add hello.html
$ git status
# On branch master
# Changes to be committed:
#   (use "git reset HEAD &lt;file&gt;..." to unstage)
#
#	modified:   hello.html
#</pre>

<p>Changes to the hello.html have been staged. hello.html의 변경사항이 추가되었다. This means that git knows about the change, 추가staging의 의미는 git이 이 변경사항을 주시한다는 뜻이다. but it is not permanent in the repository stage되었다고 해서 저장소에 저장된 상태는 아니다. The next commit will include the changes staged. 커밋될 때 추가사항이 저장될 것이다.</p>

<p>Should you decide not to commit the change, the status command will remind you that you can use the <code>git reset</code> command to unstage these changes. 변경사항을 커밋하지 않은 채로 status명령을 실행하면 <code>git reset</code> 명령을 통해 추가된 변경사항을 되돌릴 수 있다는 메시지를 보게 될 것이다.</p>
