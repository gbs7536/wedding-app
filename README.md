# Create React App으로 리액트 프로젝트 시작하기

이번 프로젝트는 **Create React App(CRA)** 으로 초기 세팅했다.
복잡한 설정 없이 리액트 개발 환경을 빠르게 구성할 수 있어서 자주 쓰이는 방식 중 하나다.

개발하면서 자주 사용하는 명령어들을 정리해봤다.
CRA를 처음 써보거나, 다시 사용할 때 참고용으로 보기 좋을 것 같다.

---

## 자주 사용하는 명령어 정리

### `yarn start` – 개발 서버 실행

개발 모드로 앱을 실행한다.
브라우저에서 [http://localhost:3000](http://localhost:3000)으로 접속하면 바로 확인 가능하다.

파일을 수정하면 자동으로 새로고침되고, 콘솔에 에러나 경고도 바로 표시돼서 빠르게 확인할 수 있다.

---

### `yarn test` – 테스트 실행

테스트 코드가 작성돼 있다면, 이 명령어로 바로 실행할 수 있다.
인터랙티브한 방식으로 동작해서 필요한 테스트만 선택적으로 돌릴 수도 있다.

> 참고: [CRA 테스트 문서](https://facebook.github.io/create-react-app/docs/running-tests)

---

### `yarn build` – 배포용 빌드

앱을 실제 배포할 때 사용하는 명령어.
빌드 결과물은 `build` 폴더에 생성되며, 최적화가 자동으로 적용돼 성능이 좋다.

파일 이름에는 해시값도 포함되어 있어서 캐싱에도 유리하다.

> 참고: [CRA 배포 문서](https://facebook.github.io/create-react-app/docs/deployment)

---

### `yarn eject` – 설정 직접 커스터마이징

CRA에서 기본으로 숨겨져 있는 설정 파일들(webpack, Babel 등)을 꺼내고 싶을 때 사용한다.
이 명령어를 실행하면 모든 설정이 프로젝트 루트로 복사되고, 직접 수정할 수 있게 된다.

다만, **한 번 eject하면 되돌릴 수 없기 때문에 정말 필요할 때만 쓰는 걸 추천**한다.
나는 이번 프로젝트에서는 사용하지 않았다.

---

## 참고한 공식 문서

* [Create React App 문서](https://facebook.github.io/create-react-app/docs/getting-started)
* [React 공식 문서](https://reactjs.org/)
