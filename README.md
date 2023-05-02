# UkkoModal 모달 라이브러리

매우 간단한 모달을 구현할 수 있는 라이브러리입니다. 타입스크립트 파일에서는 아직 적용되지 않습니다.

## 설치 방법

`npm install sample-ukko-modal`

## 사용 방법

### UkkoModal 컴포넌트 불러오기

`import { MyModal } from 'sample-ukko-modal';`

### UkkoModal 사용하기

```javascript
<MyModal trigger={<button>모달 열기</button>}>
  <h2>제목</h2>
  <p>내용</p>
</MyModal>
```

## Props

- trigger: 모달을 열기 위한 요소
- children: 모달 내부에 들어갈 컨텐츠입니다.

### Props 예시

```java
import MyModal from 'my-modal-library';

function App() {
  return (
    <div>
      <MyModal
        trigger={<button>모달이 열립니다.</button>}
      >
        <h2>제목</h2>
        <p>내용</p>
      </MyModal>
    </div>
  );
}

export default App;
```
