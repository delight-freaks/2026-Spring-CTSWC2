# 🚀 Smart Task Lifecycle Manager (STLM)

> **Python 기반의 데이터 영속성 보장형 할 일 관리 시스템**

## 1. 무엇을 하는 프로그램인가요?
단순한 텍스트 기록을 넘어, 할 일의 **생성-수정-완료-아카이빙**에 이르는 전체 라이프사이클을 관리하는 효율성 극대화 툴입니다. 데이터의 무결성을 유지하기 위해 로컬 JSON DB 구조를 채택하였으며, 사용자의 입력 오류를 방지하는 안정적인 백엔드 로직을 포함하고 있습니다.

---

## 2. 핵심 기능 (Features)
- **CRUD 연산**: 할 일의 생성(Create), 조회(Read), 상태 갱신(Update), 삭제(Delete) 지원
- **데이터 영속성(Persistence)**: 프로그램 종료 시 데이터가 `tasks.json`에 실시간 직렬화(Serialization)되어 저장
- **상태 필터링**: 완료/미완료 항목을 분리하여 조회하는 효율적 데이터 필터링
- **시간 스탬프**: 할 일이 생성된 시점을 자동으로 기록하여 관리 이력 추적

---

## 3. 실행 방법
### 사전 요구사항
- Python 3.10 이상 설치 필수
- 별도의 외부 라이브러리 설치 없이 기본 표준 라이브러리만으로 구동 가능

### 명령어
```bash
# 저장소 복제
git clone [https://github.com/사용자계정/repository-name.git](https://github.com/사용자계정/repository-name.git)

# 프로그램 실행
python main.py
