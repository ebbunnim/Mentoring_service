# ReadMe

# 구동
- LAST 디렉토리 내 ./gradlew bootRun
- http://localhost:8080/swagger-ui.html



##### 자취맨 자소서 분석 알고리즘 테스트

* 자소서 내용 예시 (잡코리아 샘플 자소서)

  [멈추지  않고 성장하는 기업과 함께하다]     

  제게 직장은 평생에 걸쳐 인생의 비전을 펼치며 함께 성장하는 동반관계입니다. 그리고 자신의 자리에서 대신할 수 없는 사람이 되는 것이  제가 가진 직업관입니다.          학과 과정과 다양한 대내외 활동을 통해 광고와 마케팅 분야에 계속해서 관심을 가져왔습니다. 역동적이고, 늘 자신을 단련해야 하는 광고  산업에 매력을 느꼈고, 미디어플래너라는 목표를 가지게 되었습니다.          또한, 단지 광고를 만드는 일뿐만 아니라, 마케팅 솔루션 제안을 통해 클라이언트에게 고객가치를 제공하는 미디어렙사의 사업분야에  매료되었습니다. 자신의 자리에서 최선을 다하는 것이 내 조직뿐만 아니라 고객사와 함께 ‘Win-Win’하는 동력이 된다는 것은 그 무엇보다  큰 비전이자 동기라고 생각합니다.          최근 기술력이 상향표준화 된 상황 속에서 광고와 미디어의 중요성은 더욱 커져가고 있습니다. 그리고 메조미디어는 온라인 광고, 마케팅  분야에서 국내 정상의 위치에 서있습니다. 메조미디어는 `기업과 함께 성장하는 인재`라는 인생의 목표를 이룰 수 있는 가장 멋진 무대입니다.  메조미디어와 함께 성장하며 새로운 솔루션, 새로운 가치를 만드는 일에 이바지하고 싶습니다.    

* ResponseBody 예시 (/last/analytics/profile)
  * value 칸에 자소서 내용 삽입 시, 1. 키워드 추출 2. 의미론적 분석 3. 핵심역량 판별

```
{
  "키워드 추출": [
    "광고",
    "성장",
    "수",
    "마케팅",
    "자신",
    "메조미디어",
    "분야",
    "것",
    "미디어",
    "자리",
    "고객",
    "가치",
    "비전",
    "일",
    "인생",
    "기업",
    "목표",
    "솔루션",
    "클라이언트",
    "산업",
    "상향",
    "직장",
    "인재",
    "평생",
    "최근",
    "다양",
    "직업",
    "표준",
    "제공",
    "조직",
    "동반",
    "플래너",
    "내외",
    "정상",
    "단련",
    "온라인",
    "무대",
    "계속",
    "최선",
    "동기",
    "사람",
    "동력",
    "매료",
    "사업",
    "글자",
    "과정",
    "속",
    "역동",
    "렙사",
    "이바지"
  ],
  "의미론적 분석": [
    "\"[멈추지 않고 성장하는 기업",
    "직장",
    "인생의 비전",
    "것",
    "학과 과정과 다양한 대내외 활동",
    "관심",
    "자신",
    "매력",
    "미디어플래너라는 목표",
    "광고",
    "일",
    "고객가치",
    "최선",
    "내 조직",
    "동력",
    "비전이자",
    "동기라고",
    "상황",
    "광고와 미디어의 중요성",
    "국내 정상의 위치",
    "인재`라는",
    "인생의 목표",
    "무대입니다.",
    "새로운 솔루션,",
    "새로운 솔루션, 새로운 가치"
  ],
  "핵심역량": [
    "성장",
    "고객",
    "비전",
    "목표"
  ]
}
```



#### 핵심역량 기준

```
 도전 
 창의 
 글로벌 
 열정 
 소통 
 전문 
 창조 
 최고 
 신뢰 
 고객 
 실행 
 협력 
 열린 
 자율 
 팀워크 
 책임 
 변화 
 실력 
 정정당당 
 존중 
 상생 
 서비스 
 실천 
 적극 
 주인의식 
 근성 
 노력 
 몰입 
 성실 
 신념 
 윤리 
 주도적 
 책임감 
 친화 
 협동 
 경쟁력 
 동료애 
 목표 
 비전 
 상생 
 성과지향 
 성장 
 소속감 
 신의 
 유연 
 윤리 
 이익 
 자신감 
 적응 
 전략 
 정성 
 리더 
 창의 
 체력 
 추진 
 패기 
 합리 
 핵심가치 
 화합 
 희생 
 주도 
 치밀 
 문제해결 
 성취지향 
 분석 
 의사소통 
 계획 
 끈기 
 인내 
```