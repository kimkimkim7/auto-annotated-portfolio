---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 안녕하세요! 김효정입니다.
    subtitle: >-
      지금까지의 경험과 성과는 저의 역량과 잠재력을 증명하는 중요한 이정표입니다. 이 과정에서 쌓은 능력으로 도전에 대한 두려움 없이,
      새로운 기술과의 대담한 조우를 통해 스스로의 가능성을 확장하며 더 큰 도약을 준비해 왔습니다. 또한, 체계적이고 전략적인 기획 능력을
      바탕으로 앞으로도 성장을 이어가고자 합니다.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: LabelsSection
    title: 나의 스킬
    subtitle: 다음과 같은 작업들을 할 수 있습니다!
    items:
      - type: Label
        label: figma (Expert)
        url: www.figma.com
      - type: Label
        label: google workspace (Expert)
        url: workspace.google.com
      - type: Label
        label: JIRA (Intermediate)
        url: www.atlassian.com
      - type: Label
        label: adobe photoshop (Intermediate)
        url: ''
      - type: Label
        label: Netlify (Intermediate)
        url: ''
      - type: Label
        label: notion (Expert)
        url: www.notion.so
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: CtaSection
    title: 저의 포트폴리오를 다운로드하고 싶나요?
    text: "저의 포트폴리오를\_*다운로드하고*\_싶다면 아래 버튼을 눌러 구글 드라이브에서\_*다운로드해 주세요*\_:)\n"
    actions:
      - type: Button
        label: 다운로드하러 가기
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
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
