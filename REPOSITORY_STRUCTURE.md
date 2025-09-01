# Swiftian Repository Structure Analysis
# Swiftian 저장소 구조 분석

> **한눈에 보는 복잡한 구조 정리** - 다국어 Jekyll 웹사이트의 체계적 구조 분석

## 📋 Overview / 개요

Swiftian은 Swift 프로그래밍 학습을 위한 다국어 지원 Jekyll 기반 웹사이트입니다. 27개 이상의 언어를 지원하는 복잡한 구조를 가지고 있습니다.

**핵심 특징:**
- 🌍 27개 언어 완전 지원
- 🎨 Jekyll 정적 사이트 생성기
- 📱 반응형 디자인
- 🎵 멀티미디어 콘텐츠 (비디오, 이미지, 오디오)
- 🤖 자동화된 콘텐츠 관리

---

## 🌳 Complete Repository Tree Structure / 전체 저장소 트리 구조

```
Swiftian/
├── 🔧 Core Configuration / 핵심 설정
│   ├── _config.yml                 # Jekyll 설정 파일
│   ├── Gemfile                     # Ruby 의존성
│   ├── Gemfile.lock               # 의존성 버전 고정
│   └── .gitignore                 # Git 무시 파일
│
├── 🏗️ Jekyll Architecture / Jekyll 아키텍처
│   ├── _layouts/                   # 페이지 레이아웃 템플릿
│   │   └── default.html           # 기본 레이아웃
│   │
│   ├── _includes/                  # 재사용 가능한 컴포넌트
│   │   ├── footer.html            # 푸터 컴포넌트
│   │   ├── locale.liquid          # 언어 설정 로직
│   │   ├── media.html             # 미디어 컴포넌트
│   │   └── video.html             # 비디오 컴포넌트
│   │
│   └── _data/                      # 사이트 데이터
│       ├── navigation.yml         # 27개 언어별 네비게이션
│       ├── languageLabels.yml     # 언어 라벨 정의
│       ├── media.yml              # 미디어 메타데이터
│       └── pages/                 # 언어별 페이지 데이터
│           ├── en.yml             # 영어 콘텐츠
│           ├── ko.yml             # 한국어 콘텐츠
│           ├── ja.yml             # 일본어 콘텐츠
│           ├── zh-hans.yml        # 중국어 간체
│           ├── zh-hant.yml        # 중국어 번체
│           └── [22 more languages]
│
├── 🌍 Multi-language Content / 다국어 콘텐츠
│   └── _languages/                # 언어별 페이지 구조
│       ├── en/                    # 영어 (기본)
│       ├── ko/                    # 한국어
│       ├── ja/                    # 일본어
│       ├── zh-hans/               # 중국어 간체
│       ├── zh-hant/               # 중국어 번체
│       ├── fr/                    # 프랑스어
│       ├── de/                    # 독일어
│       ├── es/                    # 스페인어
│       ├── it/                    # 이탈리아어
│       ├── pt/                    # 포르투갈어
│       ├── ru/                    # 러시아어
│       ├── ar/                    # 아랍어
│       ├── tr/                    # 터키어
│       ├── cs/                    # 체코어
│       ├── da/                    # 덴마크어
│       ├── nl/                    # 네덜란드어
│       ├── fi/                    # 핀란드어
│       ├── el/                    # 그리스어
│       ├── hu/                    # 헝가리어
│       ├── id/                    # 인도네시아어
│       ├── nb/                    # 노르웨이어 (부크몰)
│       ├── no/                    # 노르웨이어
│       ├── pl/                    # 폴란드어
│       ├── ro/                    # 루마니아어
│       ├── sk/                    # 슬로바키아어
│       ├── sv/                    # 스웨덴어
│       ├── uk/                    # 우크라이나어
│       └── vi/                    # 베트남어
│           │
│           └── [각 언어별 동일한 구조]
│               ├── index.md       # 메인 페이지
│               ├── coding/        # 코딩 섹션
│               │   └── index.md
│               ├── universe/      # 유니버스 섹션
│               │   └── index.md
│               ├── groove/        # 그루브 섹션
│               │   └── index.md
│               ├── creators/      # 크리에이터 섹션
│               │   └── index.md
│               └── footer/        # 푸터 페이지
│                   └── privacy.md
│
├── 🎨 Assets & Media / 에셋 및 미디어
│   └── assets/
│       ├── images/                # 이미지 파일들
│       │   ├── swiftian_logo_1024.png
│       │   ├── swiftian_logo_180.png
│       │   ├── coding_panic.gif
│       │   ├── swiftian_groove.gif
│       │   ├── iFlipbook.gif
│       │   ├── titan_color_800.jpg
│       │   ├── titan_sketch.gif
│       │   └── readme.md
│       │
│       ├── videos/                # 비디오 파일들
│       │   ├── logo.mp4
│       │   ├── swiftian_groove_720.mp4
│       │   └── readme.md
│       │
│       └── audios/                # 오디오 파일들
│           └── readme.md
│
├── 📄 Main Content Pages / 주요 콘텐츠 페이지
│   ├── index.md                   # 홈페이지 (기본 영어)
│   ├── coding/
│   │   └── index.md              # 코딩 메인 페이지
│   ├── universe/
│   │   └── index.md              # 유니버스 메인 페이지
│   ├── groove/
│   │   └── index.md              # 그루브 메인 페이지
│   ├── creators/
│   │   └── index.md              # 크리에이터 메인 페이지
│   └── footer/
│       └── privacy.md            # 개인정보처리방침
│
├── 🤖 Automation Scripts / 자동화 스크립트
│   └── py_scripts/
│       └── frontmatter/          # 프론트매터 자동 생성
│           ├── en.yaml
│           ├── ko.yaml
│           ├── ja.yaml
│           └── [24 more language yamls]
│
├── 🚀 Deployment & SEO / 배포 및 SEO
│   ├── docs/
│   │   └── CNAME                 # 커스텀 도메인 설정
│   ├── sitemap.xml               # 사이트맵
│   ├── robots.txt                # 로봇 크롤링 규칙
│   ├── 404.html                  # 404 에러 페이지
│   ├── favicon.ico               # 파비콘
│   ├── favicon.png               # PNG 파비콘
│   └── googlef020d35b429ecf1b.html # Google 사이트 인증
│
└── 🔄 DevOps & CI/CD / 개발운영 및 CI/CD
    ├── .github/
    │   └── workflows/
    │       └── jekyll.yml        # GitHub Actions 워크플로우
    └── .git/                     # Git 버전 관리
```

---

## 🔍 Detailed Component Analysis / 상세 구성 요소 분석

### 1. 🌍 Multi-language Architecture / 다국어 아키텍처

**구조의 핵심 특징:**
- **27개 언어 완전 지원**: 각 언어별로 독립적인 콘텐츠 구조
- **통일된 템플릿**: 모든 언어가 동일한 레이아웃과 기능 사용
- **자동화된 관리**: Python 스크립트로 프론트매터 일괄 생성

**언어 지원 현황:**
```
🌏 아시아-태평양     🌍 유럽              🌎 기타
├── ko (한국어)      ├── en (영어)        ├── ar (아랍어)
├── ja (일본어)      ├── fr (프랑스어)    └── ...
├── zh-hans (중문간) ├── de (독일어)
├── zh-hant (중문번) ├── es (스페인어)
├── id (인도네시아)  ├── it (이탈리아어)
└── vi (베트남어)    └── ... (18개 더)
```

### 2. 📱 Content Sections / 콘텐츠 섹션

**4개 주요 섹션:**

1. **🧑‍💻 Coding** - "Create. Explore."
   - Swift 프로그래밍 학습 콘텐츠
   - 창의적 코딩 프로젝트

2. **🌌 Universe** - "Build Your Universe"
   - 개인 프로젝트 세계 구축
   - 커뮤니티 및 생태계

3. **🎵 Groove** - "Move with the Beat"
   - 리듬 기반 생산성 도구
   - 창의성 향상 콘텐츠

4. **👨‍🎨 Creators** - "Made for Creators"
   - 크리에이터를 위한 도구와 리소스
   - 커뮤니티 쇼케이스

### 3. 🎨 Asset Management / 에셋 관리

**미디어 파일 구조:**
- **이미지**: 로고, GIF 애니메이션, 아트워크
- **비디오**: 브랜드 영상, 튜토리얼 영상
- **오디오**: 배경음악, 효과음 (준비 중)

### 4. 🤖 Automation & Scripts / 자동화 및 스크립트

**Python 자동화:**
- `frontmatter/` 디렉토리: 27개 언어별 YAML 파일 자동 생성
- 번역 워크플로우 지원
- 콘텐츠 일관성 유지

---

## 📊 Repository Statistics / 저장소 통계

```
📁 총 디렉토리: 193개
📄 총 파일: 166개
🌍 지원 언어: 27개
📱 주요 섹션: 4개
🎨 에셋 타입: 3개 (이미지, 비디오, 오디오)
```

---

## 🚀 Getting Started / 시작하기

### Development Setup / 개발 환경 설정

```bash
# 1. Jekyll 설치
gem install jekyll bundler

# 2. 의존성 설치
bundle install

# 3. 로컬 서버 실행
bundle exec jekyll serve

# 4. 브라우저에서 확인
# http://localhost:4000
```

### Adding New Language / 새 언어 추가

1. `_languages/` 에 새 언어 디렉토리 생성
2. `_data/pages/` 에 언어별 YAML 파일 추가
3. `_data/navigation.yml` 에 번역 추가
4. `py_scripts/frontmatter/` 에 YAML 설정 추가

---

## 🔗 Key Files Quick Reference / 핵심 파일 빠른 참조

| 파일/디렉토리 | 용도 | 중요도 |
|---------------|------|--------|
| `_config.yml` | Jekyll 설정 | ⭐⭐⭐ |
| `_languages/` | 다국어 콘텐츠 | ⭐⭐⭐ |
| `_data/navigation.yml` | 네비게이션 번역 | ⭐⭐⭐ |
| `assets/` | 미디어 파일 | ⭐⭐ |
| `py_scripts/` | 자동화 스크립트 | ⭐⭐ |
| `.github/workflows/` | CI/CD 설정 | ⭐ |

---

**📝 Note**: 이 문서는 Swiftian 저장소의 복잡한 구조를 이해하기 쉽게 정리한 것입니다. 실제 개발 시에는 각 언어별 콘텐츠의 일관성과 번역 품질을 유지하는 것이 중요합니다.

**🔄 Last Updated**: 2024년 12월 현재 기준으로 작성되었습니다.