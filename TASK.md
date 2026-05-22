# TASK — 전화번호 관리 시스템 (체크리스트)

## Phase 1. 사전 준비
- [x] GitHub 계정 생성
- [x] GitHub 레포지토리 생성 (sad_phonebook)
- [x] Supabase 계정 생성
- [x] Supabase 프로젝트 생성 (SAD)
- [x] Vercel 계정 생성

## Phase 2. DB 설계 및 생성
- [x] contacts 테이블 설계
  - id (PK, auto increment)
  - name (VARCHAR, 암호화 저장)
  - phone_number (VARCHAR, 암호화 저장)
  - created_at (TIMESTAMP)
- [x] Supabase SQL Editor에서 테이블 생성
- [x] RLS(Row Level Security) 활성화
- [x] 익명 접근 허용 Policy 4개 추가 (SELECT / INSERT / UPDATE / DELETE)

## Phase 3. 암호화 구현
- [x] Web Crypto API로 AES-GCM 암호화 함수 구현
- [x] PBKDF2로 암호화 키 파생
- [x] encrypt(text) 함수 구현
- [x] decrypt(base64) 함수 구현
- [x] 저장 시 암호화, 불러올 때 복호화 적용

## Phase 4. 프론트엔드 구현
- [x] 연락처 추가 UI
- [x] 연락처 목록 조회 UI
- [x] 연락처 수정 UI (모달)
- [x] 연락처 삭제 기능
- [x] 이름/전화번호 검색 기능
- [x] Supabase REST API 연동

## Phase 5. 배포
- [x] GitHub 레포지토리에 index.html 업로드
- [x] Vercel에서 GitHub 레포 연동
- [x] Vercel 자동 배포 완료
- [x] 배포 URL 확인

## Phase 6. 결과물 확인
- [x] CRUD 동작 확인 (추가/수정/삭제/조회)
- [x] 검색 동작 확인
- [x] Vercel 배포 링크에서 정상 작동 확인
- [x] DB에 저장된 값이 암호화(평문 아님) 확인

## 최종 결과물
- **Supabase**: https://dharpwxxxnqacmbppmgw.supabase.co
- **Vercel**: https://sad-phonebook-eosin.vercel.app
- **GitHub**: https://github.com/111creator/sad_phonebook
