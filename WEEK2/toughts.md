# 생각
혹시 모르잖아요, 좋은 팁이 될지. 

나중에 유용하다고 판단하면 tips나 useful_links로 옮길 것.

## Slack
- 재밌는 채널들이 많은 것 같다. ```#cat```
- 스터디용 채널도 있는 듯?
- Monitoring, Logging channel &rarr; 나중에 필요한 시스템 일정을 확인할 때 요긴 할 듯 👀

## Portal
- 단촐한 듯
- public ssh key도 연락처에 공개 된다. 🤔

## transition 외않되지
```anime.js```랑 CSS transition이랑 묘하게 잘 안 어울린다. 어차피 숫자가 줄어드는 애니메이션 효과야 CSS로 해결 할 수 없으니 anime.js로 해결횄는데, 문제는 keyframe이 2개가 생겨서 timing에 변동이 생기면 굳이 2번씩 작업해야한다...
<pre>Q. CSS transition을 anime.js로 옮길까...? 그래도 될까??</pre>
+ animation control을 기본적으로 timeline으로 했으면 좋겠다. delay는 duration+previous element(delay + duration)까지 계산해야해서 매우 불편하다.
+ Slack ```#product-study```에서는 @ronny가 제안이나 weekly를 공유하거나 아이디어를 올린다. ~~사실 이 채널에서 영감을 받아서 만들 생각을 했다~~

## 팀별 약어
+ 개발 : ENG
+ 상품 관리, 대출 심사 등 : OPS
+ 홍보 마케팅 : MKT
+ QA : ??
+ 인사팀 : PEOPLE 


## loan submain animation
- 애니메이션 효과 타이밍...
- ```LoanIndex.vue``` &rarr; *Index.vue가 page layout인 듯
- ```slot tag```?
- Default 값을 99로 줬는데, 그러면 안 될 것 같다. &larr; 왜냐하면 금액이 커질 수 있으니까? &larr; ```InterestChart.vue```에서도 ```Math.max()```로 최대값을 기준으로 비율로 나타내고 있기 때문