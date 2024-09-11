---
type: PageLayout
title: kimkimkim
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
    title: Hello!  여기는 UI/UX기획자의 페이지입니다.
    subtitle: ''
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
          - pb-28
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
    text: >
      > 지금까지 제가 쌓아온 경험과 성과는 단순한 이력 이상의 의미를 지닙니다. 

      >


      제가 쌓아온 능력을 바탕으로, 도전에 대한 두려움 없이 새로운 기술을 대담하게 받아들이며 스스로의 가능성을 확장해왔습니다. 이를 통해
      더 큰 도약을 준비하고 있으며, 앞으로도 체계적이고 전략적인 기획 능력을 바탕으로 지속적인 성장을 이루고자 합니다.
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: 프로젝트 자세히 보기 >
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
    subtitle: 저의 프로젝트들은 다음과 같아요!
  - type: LabelsSection
    title: 나의 스킬
    subtitle: 다음과 같은 작업들을 할 수 있습니다!
    items:
      - type: Label
        label: figma (Expert)
        url: www.figma.com
      - type: Label
        label: adobe photoshop (Expert)
        url: ''
      - type: Label
        label: JIRA (Intermediate)
        url: www.atlassian.com
      - type: Label
        label: google workspace (Expert)
        url: workspace.google.com
      - type: Label
        label: notion (Expert)
        url: www.notion.so
      - type: Label
        label: Netlify (Intermediate)
        url: ''
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
        url: >-
          https://drive.google.com/file/d/1kPpXiFIo3NDJofdTCzbDjO7FZEtSfSC5/view?usp=sharing
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
