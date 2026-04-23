# Zarinegobi — Official Website

**자린이와 고비 (Zarinegobi)** iOS·macOS·watchOS 가계부 앱의 공식 웹사이트.

Live: https://project-strict-money-checking.github.io/

## 목적
1. App Store 요구사항 — 개인정보처리방침 / 지원 URL 제공
2. Google AdMob Seller Disclosure용 Seller Domain
3. 앱 공식 랜딩 페이지 (한국어 · English · 日本語)

## 구조
```
/                       # 랜딩 (한국어)
/en/                    # 랜딩 (English)
/ja/                    # 랜딩 (日本語)
/privacy/               # 개인정보처리방침 (ko/en/ja)
/terms/                 # 이용약관 (ko/en/ja)
/support/               # 고객지원 & FAQ
/assets/css/style.css   # 공통 스타일
/robots.txt             # 크롤러 지시
/sitemap.xml            # 사이트맵
```

## 주의
- `/recordSpending` 경로는 앱의 Universal Link와 매칭되는 예약 경로. 파일/폴더를 생성하지 말 것.
- `.well-known/` 경로는 별도 레포에서 관리.
- CSS 1개 파일에 다크·라이트 모드 모두 포함. 외부 의존성은 Google Fonts뿐.

## 로컬 실행
```bash
python3 -m http.server 8000
```
브라우저에서 <http://localhost:8000> 열기.

## 라이선스
© 2026 Jaeyong Lee.
