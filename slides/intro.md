<h1><code>git bisect</code></h1>

Паша Финкельштейн, Lamoda

---

## А зачем

Все используют гит

<ul>
<li class="fragment" data-fragment-index="1"><code>push</code></li>
<li class="fragment" data-fragment-index="2"><code>pull</code></li>
<li class="fragment" data-fragment-index="3"><code>merge</code>?</li>
<li class="fragment" data-fragment-index="4"><code>rebase</code>???</li>
</ul>

---

# Разработчики косячат

---

## Ну поехали искать причину

---

<h2><code>git bisect <span style="color:lightgreen">start</span></code></h2>

Начинаем воспитательную работу

---

<h2><code>git bisect <span style="color:red">bad</span></code></h2>

Когда уже поломали

---

<h2><code>git bisect <span style="color:green">good</span> commit-id<sup><small>1</small></sup></code></h2>

Когда оно ещё работало

<small><sub>1. или тег. Или ещё чего</sub></small>

---

<h2><code>git bisect <span style="color:lightblue">run</span> script</code></h2>

Мыжпрограммисты!

---

<h2><code>git bisect <span style="color:red">skip</span></code></h2>

Когда наговнокодили

---

<h2><code>git bisect <span style="color:green">reset</span></code></h2>

Когда нашли виновника

---

<h2><code>git bisect <span style="color:green">visualize</span></code></h2>

![](images/bisect.png)

---

# Нашли провинившийся коммит

---

## Починили, а зря!

<h3><code>git bisect <span style="color:red">new</span></code></h3>

<h3><code>git bisect <span style="color:green">old</span></code></h3>

---

<h2><code>git <span style="color:red">blame</span></code></h2>

![](images/judge.png) <!-- .element: class="noborder" -->

---

## Спасибо!

Паша Финкельштейн

`asm0di0` at Twitter

`asm0dey` at Facebook, Telegram etc
