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
2. 때문에 유저와 화장품 간의 상호작용 데이터가 거의 없거나 적다.
3. 화장품의 성분과 유저의 특성을 바탕으로 추천하는 방법이 필요하다.

<br>

-------

<br>

추천 시스템은 협업 필터링과 내용 기반 추천으로 나뉜다.

<br>

내용 기반 추천은 컨텐츠 자체의 내용을 기반으로 비슷한 컨텐츠를 추천해주는 방법이다.  
협업 필터링은 유저들로부터 얻은 정보를 기반으로 스스로 예측하는 기술이다.

<br>

협업 필터링은 다시 Memory-based, Model-based, Hybrid로 나뉜다.

<br>

그 중에서 Memory-based 협업 필터링은 다시 사용자 기반과 아이템 기반 필터링으로 나뉜다.

<br>

사용자 기반 CF
- 데이터 크기 적고, 사용자에 대한 정보가 있는 경우에는 사용자 기반 CF가 적절
- 데이터가 풍부할 경우 정확한 추천을 함
- 가끔씩 이상한 결과를 줄 때도 있음

<br>

아이템 기반 CF
- 데이터 크기 크고, 충분한 정보가 없는 경우 아이템 기반 CF가 적절(정확도, 사용빈도가 사용자 기반보다 높다.)
- 계산이 빠름
- 업데이트를 자주해도 기존 결과에 영향이 적음
- 대기업 상업용 사이트에서 자주 사용(아마존, 넷플릭스 등)

<br>

----

<br>

필터링 종류 소개

- https://scienceon.kisti.re.kr/srch/selectPORSrchArticle.do?cn=JAKO201529539328790&dbt=NART
- https://tech.kakao.com/2021/10/18/collaborative-filtering/
- https://scvgoe.github.io/2017-02-01-%ED%98%91%EC%97%85-%ED%95%84%ED%84%B0%EB%A7%81-%EC%B6%94%EC%B2%9C-%EC%8B%9C%EC%8A%A4%ED%85%9C-(Collaborative-Filtering-Recommendation-System)/

-----

<br>

협업 필터링 예시

- https://western-sky.tistory.com/58  
- https://sunshower99.tistory.com/13