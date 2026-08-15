# Changelog

이 프로젝트의 주요 변경 사항을 기록합니다.

형식은 [Keep a Changelog](https://keepachangelog.com/ko/1.1.0/)를 따르며,
버전은 [Semantic Versioning](https://semver.org/lang/ko/)을 따릅니다.

## [1.0.0] - 2026-08-15

### Added

- 최초 UPM 패키지 배포
- **ColorReplace 컴포넌트**: HSV 색상 범위 실시간 교체 (SpriteRenderer / UI Graphic 양용)
- **CAT_ColorReplace 셰이더**: half precision, 분기 없는 수학 연산 기반 모바일 최적화
- **배칭 유지**: SpriteRenderer는 텍스처 기반 Material 공유 + PropertyBlock, UI는 설정값 해시 기반 Material 캐싱
- **ColorReplaceEditor**: 커스텀 인스펙터 (머티리얼 에셋 저장/갱신/프리뷰 — 빌드 셰이더 스트리핑 방지)
