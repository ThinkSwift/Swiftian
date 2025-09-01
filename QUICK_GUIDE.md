# Quick Navigation Guide
# 빠른 탐색 가이드

> 복잡한 Swiftian 저장소를 빠르게 이해하기 위한 가이드

## 🎯 What You're Looking For / 찾고 있는 것

### 📝 Content Management / 콘텐츠 관리
```
Want to edit content?
├── English content → Root level files (coding/, universe/, etc.)
├── Other languages → _languages/[language-code]/
└── Navigation text → _data/navigation.yml
```

### 🎨 Design & Layout / 디자인 및 레이아웃  
```
Want to change design?
├── Templates → _layouts/default.html
├── Components → _includes/
├── Styles → assets/
└── Media files → assets/images/, assets/videos/
```

### 🌍 Multi-language / 다국어
```
Want to add/edit languages?
├── New language pages → _languages/[new-lang]/
├── Navigation translations → _data/navigation.yml
├── Page data → _data/pages/[lang].yml
└── Automation → py_scripts/frontmatter/[lang].yaml
```

### ⚙️ Configuration / 설정
```
Want to change site settings?
├── Jekyll config → _config.yml
├── Dependencies → Gemfile
├── Domain → docs/CNAME
└── SEO → sitemap.xml, robots.txt
```

## 🚀 Quick Actions / 빠른 작업

### Add New Content Page / 새 콘텐츠 페이지 추가
1. Create English version in root (e.g., `new-section/index.md`)
2. Add translations in `_languages/*/new-section/index.md`
3. Update navigation in `_data/navigation.yml`
4. Test locally

### Update Existing Content / 기존 콘텐츠 업데이트
1. **English**: Edit files in root directories
2. **Other languages**: Edit files in `_languages/[lang]/`
3. **Navigation**: Update `_data/navigation.yml`
4. **Page data**: Update `_data/pages/[lang].yml`

### Add New Language / 새 언어 추가
1. Create `_languages/[new-lang]/` directory
2. Copy structure from `_languages/en/`
3. Add translation to `_data/navigation.yml`
4. Create `_data/pages/[new-lang].yml`
5. Add `py_scripts/frontmatter/[new-lang].yaml`

### Modify Design / 디자인 수정
1. **Layout**: Edit `_layouts/default.html`
2. **Components**: Edit files in `_includes/`
3. **Assets**: Add/modify files in `assets/`
4. **Styles**: Update CSS in assets or layouts

## 📂 Directory Importance Level / 디렉토리 중요도

```
⭐⭐⭐ Critical / 핵심
├── _config.yml         (Site configuration)
├── _languages/         (Multi-language content)  
├── _data/navigation.yml (Site navigation)
└── _layouts/           (Page templates)

⭐⭐ Important / 중요
├── _data/pages/        (Page data)
├── _includes/          (Reusable components)
├── assets/             (Media files)
└── Root content files  (English content)

⭐ Useful / 유용
├── py_scripts/         (Automation)
├── docs/               (Deployment)
├── .github/            (CI/CD)
└── SEO files           (robots.txt, sitemap.xml)
```

## 🔧 Development Workflow / 개발 워크플로우

```
1. Local Setup
   └── Install Jekyll, run `jekyll serve`

2. Content Changes
   ├── Edit files
   ├── Test locally
   └── Commit changes

3. New Features
   ├── Update templates
   ├── Add components
   ├── Test all languages
   └── Deploy

4. Translation Updates
   ├── Update English first
   ├── Update other languages
   ├── Check navigation
   └── Verify consistency
```

## ⚡ Pro Tips / 프로 팁

- **Consistency**: Always update all language versions when changing structure
- **Testing**: Test changes in multiple languages before deploying
- **Automation**: Use `py_scripts/` for bulk operations
- **Backup**: Always commit before major changes
- **Navigation**: Keep `_data/navigation.yml` in sync with content

## 🆘 Common Issues / 일반적인 문제

**Missing translations?**
→ Check `_data/pages/[lang].yml` and `_languages/[lang]/`

**Navigation not showing?** 
→ Verify `_data/navigation.yml` has all language entries

**New page not appearing?**
→ Check front matter and file location

**Build failures?**
→ Validate YAML syntax in `_config.yml` and data files

---

**💡 Remember**: This is a Jekyll site, so changes to `_config.yml` require a server restart!