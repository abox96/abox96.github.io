---
layout: single
title: "GameObject와 gameObject"
categories: /Unity
---

gameObject 와 GameObject
===
gameObject는 컴포넌트 입장에서 자신이 추가된 게임 오브젝트를 가리키는 변수이다.
- gameObject는 GameObject 타입의 변수이며 컴포넌트들의 기반 클래스인 MonoBehaviour에서 제공한다.

모든 컴포넌트는 gameObject 변수를 이용해 자신을 사용 중인 게임 오브젝트에 접근할 수 있다.

PlayerController 스크립트는 Player object에 추가하고 있으며, 따라서 이 스크립트에서 gameObject는 Player object를  가리키게 된다.

**즉, gameObject는 변수로 적용된 오브젝트를 가리킨다.
    GameObject는 타입이다.**

