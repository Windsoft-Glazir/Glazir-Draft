# Glazir Draft

**Glazir Draft는 브라우저에서 2D 도면과 3D 모델을 열고 작성·편집하는 Windsoft 웹 CAD입니다.** Community 기본 기능은 설치나 가입 없이 사용할 수 있습니다.

[브라우저에서 Glazir Draft 시작](https://draft.windsoft.co.kr/) · [공식 제품 소개](https://windsoft.co.kr/glazir-draft.html)

## 주요 기능

- **2D 작도 및 DXF 활용** — 새 도면을 그리거나 DXF를 불러옵니다. 스냅과 레이어를 사용해 기준을 맞추고 기존 도면을 편집할 수 있습니다.
- **3D 모델링 및 검토** — 닫힌 면을 압출해 입체 형상을 만듭니다. 모델 트리, 레이어 표시·격리, 단면으로 객체와 속성을 살펴봅니다.
- **Revit 연계** — Revit에서 Glazir Exporter로 RVT 모델을 GLZ로 내보내면 Draft에서 열어 검토할 수 있습니다. 지원되는 배치·매개변수 변경 요청은 GLZ에 저장하고 Revit에서 검토해 적용합니다.
- **세트·공정 및 4D 재생** — 객체를 세트로 묶고 일정을 연결해 시공 순서를 재생합니다. 물량 집계 결과의 Excel 내보내기는 Pro 이상에서 제공합니다.
- **팀 공동 작업** — Team에서 수정 요청과 진행 상황을 공유하고 변경 이력을 관리합니다.

## 처음 사용하는 순서

1. [Glazir Draft](https://draft.windsoft.co.kr/)를 열고 새 도면을 시작하거나 파일 메뉴에서 GLZ를 엽니다. 기존 2D 도면은 DXF 가져오기로 시작할 수 있습니다.
2. 실제 길이를 알고 있는 부분을 측정해 단위와 배율을 확인합니다. 밑그림과 새 작업을 별도 레이어로 나누고 필요하면 밑그림을 잠급니다.
3. 2D 편집을 하거나 스냅으로 닫힌 면을 만든 뒤 높이 또는 두께를 지정해 압출합니다. 3D 모델은 객체 트리와 단면으로 확인합니다.
4. 작업 결과를 다른 이름의 GLZ로 저장한 뒤 다시 열어 형상, 단위, 레이어와 필요한 속성이 의도대로 저장됐는지 확인합니다.

Revit 모델에서 시작하려면 [Glazir Exporter](https://github.com/Windsoft-Glazir/Glazir-Exporter)로 먼저 GLZ를 준비하세요. 원본 RVT에 변경을 반영하려면 Revit에서 별도로 검토하고 적용해야 합니다.

## 실행·설치 및 에디션 안내

Glazir Draft는 웹 앱입니다. PC 브라우저에서 열어 시작할 수 있으며 별도 설치 파일은 없습니다. Revit과 파일을 교환할 때는 Revit용 Glazir Exporter 설치가 필요합니다.

| 에디션 | 주요 범위 |
| --- | --- |
| Community | 기본 작도·편집, DXF 가져오기, GLZ 열기·로컬 저장, 모델 검토, 4D 재생 |
| Pro | 자동 인식, PDF 벡터 가져오기, IFC 내보내기, 물량 Excel 내보내기 등 |
| Team | Pro 기능, 팀 공동 작업, 수정 요청 공유 및 진행 상황 확인, 변경 이력 공유 |

- [시작 가이드](https://windsoft.co.kr/glazir-draft-getting-started.html) · [사용 설명서](https://windsoft.co.kr/Glazir-draft-manual.html) · [최신 에디션 비교](https://windsoft.co.kr/glazir-draft.html#editions)
- [Glazir Exporter 설치 파일](https://github.com/Windsoft-Glazir/Glazir-Exporter/releases/latest)

## English summary

Glazir Draft is a browser-based CAD tool for 2D drafting, DXF import, 3D modeling, and GLZ model review. Open a GLZ file or import a DXF, check units and layers, edit the model, and save your work locally as GLZ. Community covers the basic browser workflow. Pro adds features such as PDF vector import and Excel quantity export, while Team adds collaboration and shared review. Use the Revit add-in Glazir Exporter to prepare GLZ files and exchange supported changes with Revit.

- [Open Glazir Draft](https://draft.windsoft.co.kr/) · [Product overview](https://windsoft.co.kr/glazir-draft-en.html) · [Getting started](https://windsoft.co.kr/glazir-draft-getting-started-en.html) · [User manual](https://windsoft.co.kr/Glazir-draft-manual-en.html)
