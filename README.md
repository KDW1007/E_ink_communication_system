# Visible Memory

E-ink의 bistable 상태를 흑백 2D 패턴으로 기록하고, 전원 OFF 후에도 카메라로 읽어 데이터를 복원하는 프로젝트.

저장소: private — 초대된 collaborator만 접근 가능.

## 팀 / 역할

| 이름 | GitHub | 역할 | 작업 브랜치 | 디렉터리 |
|------|--------|------|-------------|----------|
| dwkang | [@KDW1007](https://github.com/KDW1007) | 웹 통합 | `web/dwkang` | [`web/`](web/) |
| 김소이 | TBD | QR 입출력 소프트웨어 | `qr/kimsoyi` | [`qr/`](qr/) |
| 이현민 | [@jjd1627-sudo](https://github.com/jjd1627-sudo) (초대 수락 대기) | 하드웨어 | `hardware/hyunmin` | [`hardware/hyunmin/`](hardware/hyunmin/) |
| 최서현 | TBD | 하드웨어 | `hardware/seohyun` | [`hardware/seohyun/`](hardware/seohyun/) |

## 협업 규칙

1. `main`에는 직접 push하지 않는다. 각자 브랜치에서 작업한다.
2. 작업이 끝나면 PR을 열고, **저장소 소유자(KDW1007 / dwkang)**가 `main`으로 머지한다.
3. 자신의 역할 디렉터리 위주로 수정한다. 공유 인터페이스가 필요하면 PR 설명에 적는다.

## 디렉터리

```
qr/                 # QR 인코딩·디코딩 / 카메라 입출력
web/                # 웹 UI·API·파이프라인 통합
hardware/
  hyunmin/          # MCU·E-ink 구동 등
  seohyun/          # MCU·전원·기구 등
docs/               # 제안서·스펙·실험 기록
```
