# my_test_lint

간단한 Python 프로젝트 템플릿입니다. 이 저장소는 테스트와 린팅 설정을 실험하거나 작은 예제를 빠르게 시작하는 용도로 사용합니다.

## 설명
- 최소한의 파일 구조와 예제 코드 (`file1.py`)를 포함합니다.
- 테스트, 린트 도구를 적용해보는 용도로 적합합니다.

## 요구사항
- Python 3.8 이상

## 사용법
1. 가상환경 생성 (선택)
```bash
python -m venv .venv
source .venv/bin/activate  # WSL 또는 macOS/Linux
```
2. 필요한 패키지 설치 (필요한 경우)
```bash
pip install -r requirements.txt
```
3. 테스트 실행 (프로젝트에 테스트가 추가된 경우)
```bash
pytest
```
4. 린트/스타일 검사 예시
```bash
# ruff 또는 flake8, black 등 사용
ruff check .
```

## 기여
- 간단한 변경사항은 풀 리퀘스트로 보내주세요.

## 라이선스
- 프로젝트 루트의 `LICENSE` 파일을 참조하세요.
