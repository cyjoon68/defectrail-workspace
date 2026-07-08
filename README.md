# DefectRail Workspace

DefectRail은 Inspection AI 불량 데이터를 lot 단위로 분석하고 재검수 큐로 연결하는 제조 품질 포트폴리오 프로젝트입니다.

## 저장소 구조

```text
defectrail-workspace/
  defectrail-fe/  # Next.js 품질 대시보드
  defectrail-be/  # FastAPI + SQLAlchemy async REST API
```

FE/BE는 Git submodule로 연결되어 있습니다.

## 프로젝트 링크

- FE: https://github.com/defectrail-labs/defectrail-fe
- BE: https://github.com/defectrail-labs/defectrail-be
- Personal mirror: https://github.com/cyjoon68/defectrail-workspace

## 실행

```bash
git clone --recurse-submodules https://github.com/defectrail-labs/defectrail-workspace.git
```

## 포트폴리오 포인트

Next.js 기반 품질 분석 화면과 Python async REST API를 실제 서비스 repo 구조처럼 분리했습니다.
