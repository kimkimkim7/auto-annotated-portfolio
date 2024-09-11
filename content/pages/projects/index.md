---
type: ProjectFeedLayout
title: 내 프로젝트
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 50
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  showDate: false
  showDescription: true
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-a
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: left
bottomSections:
  - type: CtaSection
    title: 저의 포트폴리오를 다운로드하고 싶나요?
    text: "저의 포트폴리오를\_*다운로드하고*\_싶다면 아래 버튼을 눌러 구글 드라이브에서\_*다운로드해 주세요*\_:)\n"
    actions:
      - type: Button
        label: 다운로드하러 가기
        altText: ''
        url: >-
          https://drive.google.com/file/d/1whPo7EIHB-1Hj59YHwwXGLZwIX7eYfh9/view?usp=sharing
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
---
