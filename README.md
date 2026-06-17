# 클라우드·AI 서비스 결제·리소스 완전 정리 (101)

컴퓨터가 익숙하지 않은 분도 따라 할 수 있도록, **클라우드·AI 서비스(GCP·OpenAI)의 결제와 자원을 완전히 정리하는 방법**을 화면 사진과 함께 단계별로 설명한 교안입니다. 산출물: 📖 [주피터북](https://power080900.github.io/howToCancelPayment/).

## 세션 구성 (3세션)
| 세션 | 내용 | 입력 이미지 |
|---|---|---|
| 세션 1 | GCP 가상 컴퓨터(VM 인스턴스) 삭제 | `01_input/images/session1_deleteVmEngine` |
| 세션 2 | GCP 결제계정 폐쇄·프로젝트 결제 중지·카드 삭제 | `01_input/images/session2_deleteGcpCard` |
| 세션 3 | OpenAI(챗GPT) API 키·결제 카드 삭제 | `01_input/images/session3_openAI` |

## 폴더 (번호 = 진행순서)
```
101/101_howToCancelPayment/
├── course.yaml             산출물 선택 + 메타
├── 01_input/               ① 입력 (참고자료·원본이미지)
│   ├── reference/           PPT·PDF
│   └── 활용_images/         원본 스크린샷
├── 02_draft/               ② 브레인스토밍·초안
│   ├── logs/                Claude 대화·브레인스토밍 로그
│   └── 초안.md
├── 03_src/book/            ③ 집필 소스 (_config·_toc·*.md·images)
└── 04_output/jupyter_book/ ④ 빌드 결과 (자동 생성, git 제외)
```

## 로컬 빌드 (Jupyter Book v1)
```bash
pip install -r ../../requirements.txt
jupyter-book build 03_src/book/
cp -r 03_src/book/_build/html/* 04_output/jupyter_book/   # (선택) output에 복사
# 결과: 03_src/book/_build/html/index.html
```
Windows(PowerShell, venv 권장 — 루트에서 생성):
```powershell
.venv\Scripts\jupyter-book.exe build 101\101_howToCancelPayment\03_src\book\
start 101\101_howToCancelPayment\03_src\book\_build\html\index.html
```

## 배포
저장소 루트 `main` 푸시 시 `.github/workflows/deploy.yml`가 `03_src/book/`을 빌드해 GitHub Pages로 배포합니다.

---
> 화면 사진의 개인정보(이름·이메일·카드번호·프로젝트 ID 등)는 모두 가려져 있습니다.
