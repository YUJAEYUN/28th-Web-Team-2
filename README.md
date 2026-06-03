# YAPP 28기 웹 2팀

프론트엔드 · 백엔드 · 문서를 한곳에서 관리하는 통합 레포지토리입니다.
`frontend/`, `backend/`는 git submodule로 각 레포를 참조합니다.

## 구성

| 디렉터리 | 설명 | 레포 |
|---------|------|------|
| `frontend/` | 프론트엔드 (서브모듈) | [28th-Web-Team-2-FE](https://github.com/YAPP-Github/28th-Web-Team-2-FE) |
| `backend/`  | 백엔드 (서브모듈) | [28th-Web-Team-2-BE](https://github.com/YAPP-Github/28th-Web-Team-2-BE) |
| `docs/`     | 프로젝트 문서 | - |

## 클론

서브모듈까지 한 번에 받으려면:

```bash
git clone --recurse-submodules https://github.com/YAPP-Github/28th-Web-Team-2.git
```

이미 클론했다면:

```bash
git submodule update --init --recursive
```

## 서브모듈 최신화

각 서브모듈을 원격의 최신 커밋으로 갱신:

```bash
git submodule update --remote
```

> 서브모듈(FE/BE)은 private 레포입니다. 내용을 받으려면 해당 레포 접근 권한이 필요합니다.
