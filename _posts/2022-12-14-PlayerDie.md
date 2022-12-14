---
layout: single
title: "오브젝트 비활성화"
categories: /Unity
---

```C#
public void Die(){
// 자신의 게임 오브젝트를 비활성화
gameObject.SetActive(false);
}
```
SetActive()는 게임 오브젝트를 나타내는 GameObject 타입에 내장되어 있는 메서드이다.
입력으로 bool 값을 받으며 SetActive(true)가 실행되면 게임 오브젝트를 활성화한다.
위의 사용한 gameObject.SetActive(false);는 다음과 같은 순서로 자신의 게임 오브젝트를 비활성 시킨다.
1. gameObject를 사용해 자신의 게임 오브젝트에 접근
2. 접근한 게임 오브젝트의 SetActive(false);를 실행
***
