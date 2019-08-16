---
view: page
title: "4. 저장소의 상태 확인하기"
---

<h3>목표</h3>

<ul><li>저장소의 상태를 확인하는 방법을 배운다</li></ul>

<h2><em>01</em> 저장소의 상태 확인</h2>

<p><code>git status</code> 명령어로 저장소의 현재 상태를 확인 할 수 있다.</p>

<h4 class="h4-pre">실행:</h4>

<pre class="instructions">git status</pre>

<p>결과는</p>

<h4 class="h4-pre">결과:</h4>

<pre class="sample">$ git status
# On branch master
nothing to commit (working directory clean)</pre>

<p>실행 결과를 보면 이 폴더에는 commit 할 것이 없고 작업 폴더의 현재 상태가 저장소에 반영이 되어 있다는 것을 알 수 있다.</p>

<p>앞으로 우리는 작업 폴더와 저장소의 상태를 지속적으로 모니터링하기 위해 <code>git status</code> 명령을 사용할 것이다.</p>
