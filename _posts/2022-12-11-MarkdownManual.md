---
layout: single
title: "마크다운 설명서"
categories: CategoryA
---

#제목(Header)
======
제목1 - h1
================

제목2 - h2
----------------------

# 제목1 - h1
## 제목2 - h2
### 제목3 - h3
#### 제목4 - h4
##### 제목5 - h5
###### 제목6 - h6
-------


#마크다운 처리를 억제하는 방법
======
<MTMarkdownOptions output = 'raw'>
# hello H1
</MTMarkdownOptions>
`이 안에 있는 마크다운 혹은 마크업은 억제됌 : 예) 밑줄억제 <u>밑줄</u>`
***


#강조(Emphasis)
===============
*이텔릭체* 표시는 `*별표(asterisks)* or _언더바(underscore)_`
**두껍게** 표시는 `**별표 두개(double asterisks)** or __언더바 두개(double underscore)__`
**_이텔릭체와 두껍게 표시를 같이 사용가능하다._** `**_이텔릭체와 두껍게 표시_**
~~취소선~~은 `~~물결표시(tilde)~~` 사용
<u>밑줄</u>은 `<u></u>` 사용
***


#목록(List)
=====
`<ol></ol>큰 목록으로 최상위 목록에 사용`
`<ul></ul>작은 목록으로 최상위 목록 속 다른 목록에 사용`
`<li></li> : ` <li>1번</li>
1. 항목앞에 사용 시 순서 적용
1) 이 또한 항목앞에 사용 시 적용
`-, *, + : 순서 없는 항목에 적용` 
- - 리스트
* * 리스트
+ + 리스트

#### 하위 리스트 표시
##### - 상위리스트안에서 다음 리스트 작성 시 들여쓰기하면 하위리스트로 들어감
1. 상위리스트
	1. 하위리스트
	2. 하위리스트
2. 상위리스트
***


#체크박스(Check box)
=====
##### - []입력으로 리스트를 체크 박스 형태로 표시가능([] 앞뒤로 space 입력)

- [ ] 체크박스
`- [ ] 체크박스`
 ***


#코드강조 
====
##### - 블록코드 
```C#
printf(Hello world!);
printf(Hello world!);
```
##### - 인라인(inline)코드 강조
<code>printf(Hello world!);</code> `<code>printf(Hello world!);</code>`
<pre>printf(Hello world!);</pre> `<pre>printf(Hello world!);</pre>`
***



#수평선 
====
---
---(Hyphens)

***
*** (Asterisks)

___
___ (Underscores)



#줄바꿈
===
`<br>`
줄바꿈은 <br>로 사용하면 된다.
***



#테이블(table)
===
```
|제목|내용|설명|
|------|---|---|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
```
|제목|내용|설명|
|------|---|---|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|

- #### **표 정렬**
-  : 문자로 정렬을 할 수 있다.
```
|제목|내용|설명|
|:---|---:|:---:|
|왼쪽정렬|오른쪽정렬|중앙정렬|
|왼쪽정렬|오른쪽정렬|중앙정렬|
|왼쪽정렬|오른쪽정렬|중앙정렬|
```
|제목|내용|설명|
|:---|---:|:---:|
|왼쪽정렬|오른쪽정렬|중앙정렬|
|왼쪽정렬|오른쪽정렬|중앙정렬|
|왼쪽정렬|오른쪽정렬|중앙정렬|


|제목|내용|설명|
|:---|:---:|---:|
||중앙||
|||오른쪽|
|왼쪽||
