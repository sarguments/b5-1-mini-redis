# B5-1 정보를 엄청 빠르게 찾아주는 작은 저장소 만들기

코딧세이 AI 올인원 본과정 B5-1 미션 저장소입니다.

## 범위
Python CLI Mini Redis·해시맵 체이닝·이중연결리스트 LRU·힙 TTL·dict/collections 사용 금지

## 개발 환경
Python 3.8 이상을 사용하는 CLI 프로그램입니다. 실행 환경을 준비한 뒤 실제 버전과 시작 명령을 기록합니다.

### 새 환경에서 준비

Git을 설치한 뒤 새 기기에서 저장소를 받습니다.

```bash
git clone https://github.com/sarguments/b5-1-mini-redis.git
cd b5-1-mini-redis
```

Python 3.8 이상을 설치한 뒤 저장소 루트에서 실행합니다. 가상환경은 기기마다 새로 만듭니다.

```bash
python3 --version
python3 -m venv .venv
.venv/bin/python --version
```

아직 실행할 기능 코드가 없습니다. 실행 명령과 외부 의존성은 실제 구현 후 기록합니다.

## 준비 상태
Python 3.14.3 가상환경을 준비했습니다. 해시맵·이중 연결 리스트·힙과 LRU·TTL은 직접 구현합니다.
dict·set·collections로 핵심 자료구조를 대체하지 않으며 네트워크와 파일 영속성은 구현 범위에 포함하지 않습니다.
