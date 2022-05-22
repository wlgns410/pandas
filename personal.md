# 인프런 python 개인 추천 알고리즘 강의 요약

<br>

- 강의 보고 공부중


---

<br>

## 어떤 필터링을 기준으로 추천시스템을 구현할 것인가?

<br>

내 지금 상황 : 어떤 필터링 방법을 적용해야하지?

<br>

1. 현재 많은 유저가 있는 사이트가 아니라 처음부터 만드는 사이트이다.
2. 때문에 유저와 화장품 간의 상호작용 데이터가 없다.
3. 그래서 협업 필터링을 적용하기에는 어려워 보인다.
4. 화장품의 성분과 유저의 특성을 바탕으로 추천하는 방법이 필요하다.

<br>

그래서 콘텐츠 기반 필터링으로 테스트를 해야할 것 같은 생각이 들었다.

<br>

필터링 종류 소개

- https://scienceon.kisti.re.kr/srch/selectPORSrchArticle.do?cn=JAKO201529539328790&dbt=NART
- https://tech.kakao.com/2021/10/18/collaborative-filtering/


-----

<br>

협업 필터링 예시

- https://western-sky.tistory.com/58  
- https://sunshower99.tistory.com/13