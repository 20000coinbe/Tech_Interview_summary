## RESTful API

- **REST 아키텍처의 제약조건을 준수**하는 API
- Resource(리소스)의 상태를 JSON, HTML, XLT 등의 형태로 전송

### 제약조건

- Uniform: 모든 Platform에서 사용가능하며, URL을 통해 리소스 조작가능
- stateless: **상태정보를 저장하지 않으며**, Request(요청)에 대해서 단순처리
- Cachable: 캐시 사용가능

  ※ Cach(캐시)란...

  - 자주사용되는 Document(문서)의 사본을 자동보관

- 자체표현구조: **METHOD + URL** 형태로 구성
- 클라이언트ㆍ서버구조
- 계층형 구조

### 설계

1. **URI는 정보의 자원을 표현**해야 한다(리소스명은 동사보다 명사를 사용한다)
2. 자원에 대한 행위는 **HTTP METHOD(GET, POST, PUT, DELETE 등)으로 표현**해야 한다

#### 참고
