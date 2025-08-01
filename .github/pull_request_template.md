## 과제 체크포인트

### 배포 링크

<!--
배포 링크를 적어주세요
예시: https://<username>.github.io/front-6th-chapter1-3/

배포가 완료되지 않으면 과제를 통과할 수 없습니다.
배포 후에 정상 작동하는지 확인해주세요.
-->

### 기본과제

#### equalities

- [ ] shallowEquals 구현 완료
- [ ] deepEquals 구현 완료

#### hooks

- [ ] useRef 구현 완료
- [ ] useMemo 구현 완료
- [ ] useCallback 구현 완료
- [ ] useDeepMemo 구현 완료
- [ ] useShallowState 구현 완료
- [ ] useAutoCallback 구현 완료

#### High Order Components

- [ ] memo 구현 완료
- [ ] deepMemo 구현 완료

### 심화 과제

#### hooks

- [ ] createObserver를 useSyncExternalStore에 사용하기 적합한 코드로 개선
- [ ] useShallowSelector 구현
- [ ] useStore 구현
- [ ] useRouter 구현
- [ ] useStorage 구현

### context

- [ ] ToastContext, ModalContext 개선

## 과제 셀프회고

<!-- 과제에 대한 회고를 작성해주세요 -->

### 기술적 성장

<!-- 예시
- 새로 학습한 개념
- 기존 지식의 재발견/심화
- 구현 과정에서의 기술적 도전과 해결
-->

### 자랑하고 싶은 코드

<!-- 예시
- 특히 만족스러운 구현
- 리팩토링이 필요한 부분
- 코드 설계 관련 고민과 결정
-->

### 개선이 필요하다고 생각하는 코드

<!-- 예시
- 특히 만족스러운 구현
- 리팩토링이 필요한 부분
- 코드 설계 관련 고민과 결정
-->

### 학습 효과 분석

<!-- 예시
- 가장 큰 배움이 있었던 부분
- 추가 학습이 필요한 영역
- 실무 적용 가능성
-->

### 과제 피드백

<!-- 예시
- 과제에서 모호하거나 애매했던 부분
- 과제에서 좋았던 부분
-->

## 학습 갈무리

### 리액트의 렌더링이 어떻게 이루어지는지 정리해주세요.

<!-- 예시
- 리액트의 렌더링 과정
- 리액트의 렌더링 최적화 방법
- 리액트의 렌더링과 관련된 개념들 (예: Virtual DOM, Reconciliation 등)
- 리액트의 렌더링과 관련된 라이프사이클 메서드
- 리액트의 렌더링과 관련된 Hooks (예: useMemo, useCallback 등)
-->

### 메모이제이션에 대한 나의 생각을 적어주세요.

<!-- 예시
- 메모이제이션이 언제 필요할까?
- 메모이제이션을 사용하지 않으면 어떤 문제가 발생할까?
- 메모이제이션을 사용했을 때의 장점과 단점은 무엇일까?
- 메모이제이션을 사용하지 않고도 해결할 수 있는 방법은 무엇일까?
-->

### 컨텍스트와 상태관리에 대한 나의 생각을 적어주세요.

<!-- 예시
- 컨텍스트와 상태관리가 필요한 이유는 무엇일까?
- 컨텍스트와 상태관리를 사용하지 않으면 어떤 문제가 발생할까?
- 컨텍스트와 상태관리를 사용했을 때의 장점과 단점은 무엇일까?
- 컨텍스트와 상태관리를 사용하지 않고도 해결할 수 있는 방법은 무엇일까?
- 컨텍스트와 상태관리를 사용할 때 주의해야 할 점은 무엇일까?
-->

## 리뷰 받고 싶은 내용

<!--
피드백 받고 싶은 내용을 구체적으로 남겨주세요
모호한 요청은 피드백을 남기기 어렵습니다.

참고링크: https://chatgpt.com/share/675b6129-515c-8001-ba72-39d0fa4c7b62

모호한 질문의 예시)
- 무엇을 질문해야 할지 몰라서 코치님이 보시기에 고쳐야할것들 전반적으로 피드백 부탁드립니다.
- 코드 스타일에 대한 피드백 부탁드립니다.
- 코드 구조에 대한 피드백 부탁드립니다.
- 개념적인 오류에 대한 피드백 부탁드립니다.
- 추가 구현이 필요한 부분에 대한 피드백 부탁드립니다.

구체적인 질문의 예시)
- 파일A의 함수B와 그 안의 변수명을 보면 직관성이 떨어지는 것 같습니다. 함수와 변수 이름을 더 명확하게 지을 방법에 대해 조언해 주실 수 있나요?
- 현재 파일 단위로 코드를 분리했지만, 이번 주차 발제를 기준으로 봤을 때 모듈화나 계층화에서 부족함이 있는 것 같습니다. 특히 A와 B 부분에서 모듈화를 더 진행할지 그대로 둘지 고민하였습니다. (...구체적인 고민 사항 적기...). 코치님의 의견이 궁금합니다.
- 옵저버 패턴을 사용해 상태 관리 로직을 구현해 보려 했습니다. 제가 구현한 코드가 옵저버 패턴에 맞게 잘 구성되었는지 검토해 주시고, 보완할 부분을 제안해 주실 수 있을까요?
- 컴포넌트 A를 테스트 할 때 B와의 의존성 때문에 테스트 코드를 작성하려다 포기했습니다. A와 B의 의존성을 낮추고 테스트 가능성을 높이는 구조 개선 방안이 있을까요?

과제에서 디테일한 피드백을 받기 위해선 여러분의 생각을 디테일하게 표현해주셔야 한답니다.

가령, "전반적으로 이 라우터 구조가 규모가 커졌을 때 유지보수나 기능 확장에 유리한지, 아니면 리팩토링이 필요할지 조언을 받고 싶습니다" 라는 질문이 있을 때, 답변드리기가 어려워요. 
이럴 때는 "기능 확장" 상황을 먼저 가정해봐야합니다. 테스트의 엣지케이스를 작성하는 것 처럼요! 그리고 그 상황에 대해 내가 작성한 코드가 이러저러한 이유 때문에 대응가능할 것 같은데 혹시 더 고려해야할 부분이 있을지를 물어보는거죠.

이건 코치에게 이야기할 때 뿐만 아니라 팀원에게 이야기할 때에도 동일해요. 여러분의 컨텍스트를 명확하게 전달하지 않으면 여러분과 이야기할 때 시간이 무척 오래 걸린답니다.

특히 멘토링 처럼 동기적으로 이루어지는 커뮤니케이션에서는 위와 같은 질문을 던져도, 상호 피드백으로 질문을 함께 만들어갈 수 있지만, 과제 피드백 처럼 비동기 방식 + 1회용 질문일 때에는 좋은 답변을 드리기가 어려운점 인지 부탁드립니다 ㅠㅠ
-->
