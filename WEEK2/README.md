# Week1
## Code base overview
Repository는 크게 3개
+ Back-end (Spring, Java+Kotlin) ```lendit```, ```lendit-shop```
> Spring 내 JSP를 ```.vue``` component로 옮기는 과정이 진행중이다.
+ Front-end (VUe+JQuery) ```lendit-front-end```
   + ```admin``` : credit.lendit.co.kr (repo in repo)
   + ```web``` : lendit web service 일부 (repo in repo)


## 주기적으로 확인해야 하는 Slack Channel (by priority)
1. team-engineer
   - lendit 관련 bomber 반드시 유의 (dev에 업로드 했는데 오류가 발생하면 당황하지 말고 master를 deploy 하도록 하자)
2. front-end


## deploy
- Slack ```#team-engineering```에서 쓸 수 있는 명령어

   - Dev Server 목록 확인: !server list
   - Dev Server 할당 받기: !server dev acquire
   - Dev Server 사용 완료: !server dev release
   - 추가 명령어 확인: !server

> **DEV1은 OPS 팀도 같이 사용 중이므로 Major 배포 시 신중할 것** [출처](https://lendit.atlassian.net/wiki/spaces/DEV/pages/479166466/Dev+Admin+Web)

## etc
- Weekly 1 on 1 w/ mark
- nickname이나 실명 때문에 헷갈린다면, [포탈의 연락처](https://portal.lenditbank.xyz/contacts)를 확인하도록 합시다~~
