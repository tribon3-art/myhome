---
title: '홈'
date: 2024-01-01
type: landing

sections:
  # ══════════════════════════════════════════════════════
  # HERO - 메인 슬로건
  # ══════════════════════════════════════════════════════
  - block: hero
    id: top
    content:
      eyebrow: 뉴저지 호손 | 20년 웰니스 전문가
      title: 말과 행동이 일치하는 정직함으로, 당신의 **건강한 내일**을 디자인합니다.
      text: 투명한 신뢰 위에서 피어나는 건강하고 풍요로운 라이프스타일. 뉴저지 호손을 기반으로 20년 동안 꾸준함의 가치를 증명해 온 웰니스 파트너 주정숙입니다. 진심을 담은 상담으로 당신의 일상을 케어합니다.
      primary_action:
        text: 웰니스 상담 신청하기
        url: "#contact"
        icon: chat-bubble-left-right
        style: gradient
      secondary_action:
        text: 주정숙의 스토리 보기
        url: "#about"
        icon: user-circle
        style: ghost
      trust:
        text: "**20년** 웰니스 경력 | **15년** 홈케어 전문 | 뉴저지 기반"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      section_break:
        fade_bottom: "#0c4a6e"
      background:
        color: "#0a2540"
        gradient:
          type: radial
          start: "rgba(14,165,233,0.40)"
          end: "transparent"
          position: "50% -10%"
          shape: ellipse
          size: "80% 80%"
        gradient_mesh:
          enable: true
          style: orbs
          intensity: medium
          animation: pulse
          colors: ["sky-400/30", "emerald-400/20"]
          orb_count: 2
          positions: ["top-1/3 left-1/4", "bottom-1/3 right-1/4"]
          sizes: ["w-[32rem] h-[32rem]", "w-[26rem] h-[26rem]"]

  # ══════════════════════════════════════════════════════
  # STATS - 핵심 수치
  # ══════════════════════════════════════════════════════
  - block: stats
    content:
      items:
        - statistic: "20년+"
          description: |
            웰니스 &  
            네트워크 마케팅 경력
        - statistic: "15년+"
          description: |
            전문 홈케어  
            에이전트 경력
        - statistic: "CHHA"
          description: |
            공인 홈 헬스  
            에이드 자격 보유
        - statistic: NJ
          description: |
            뉴저지 호손  
            동부 지역 기반
    design:
      layout: minimal
      numbers_gradient: true
      css_class: "bg-sky-950"
      spacing:
        padding: ["3rem", 0, "3rem", 0]

  # ══════════════════════════════════════════════════════
  # ABOUT - 소개
  # ══════════════════════════════════════════════════════
  - block: features
    id: about
    content:
      subtitle: 소개 (About Me)
      title: 가장 정직한 꾸준함이 가장 위대한 변화를 만듭니다.
      text: |
        사람의 인생에서 '건강'과 '일상'을 지키는 것보다 가치 있는 일은 없다는 믿음으로 시작했습니다. 지난 15년간 홈케어 에이전트로서 가장 가까이서 이웃을 돌보았고, 20년간 네트워크 마케팅 전문가로 활동하며 진정성 있는 웰니스 라이프를 전파해 왔습니다. 화려한 말보다 묵묵한 행동으로 신뢰의 길을 걸어왔습니다.
      items:
        - name: 20년의 웰니스 전문성
          icon: sparkles
          description: 암웨이 등 검증된 글로벌 브랜드 제품에 대한 깊은 이해와 맞춤형 큐레이션 능력으로 고객 한 분 한 분께 최적의 솔루션을 제안합니다.
        - name: 언행일치 (Integrity)
          icon: shield-check
          description: 말과 행동이 일치하는 투명한 비즈니스로 파트너와 평생의 신뢰를 구축합니다. 진심은 언제나 통하며, 언행일치는 비즈니스의 시작이자 전부입니다.
        - name: 15년의 라이프 케어 노하우
          icon: heart
          description: 홈케어 경력에서 우러나오는 섬세함으로 개인별·가정별 맞춤 건강 컨설팅을 제공합니다. 가장 가까이서, 가장 진심으로 케어합니다.
    design:
      css_class: "bg-white"

  # ══════════════════════════════════════════════════════
  # SERVICES - 대표 브랜드 & 제품
  # ══════════════════════════════════════════════════════
  - block: features
    id: services
    content:
      subtitle: 대표 브랜드 & 서비스
      title: 검증된 글로벌 브랜드로 당신의 건강과 일상을 케어합니다.
      text: 세계적으로 인정받은 제품들을 20년간의 전문 경험과 함께 가장 정직하게 소개합니다.
      items:
        - name: 뉴트리라이트 (Nutrilite)
          icon: beaker
          description: 90년 이상의 역사를 가진 세계적인 건강기능식품 브랜드. 씨앗부터 완제품까지 철저히 관리된 자연의 영양으로 개인별 맞춤형 웰니스 라이프를 제안합니다.
        - name: 아티스트리 (Artistry)
          icon: sparkles
          description: 피부 건강의 근본을 케어하는 비건 보태니컬 스킨케어. 겉만 꾸미는 아름다움이 아닌 피부 스스로의 자생력을 높이는 웰니스 뷰티를 선사합니다.
        - name: 이스프링 & 애트모스피어
          icon: home
          description: 전문 홈케어 전문가가 직접 검증하고 추천하는 친환경 홈 시스템. 세계 판매 1위 정수기 이스프링과 고성능 공기청정기 애트모스피어로 가족의 물과 공기를 가장 안전하게 케어합니다.
    design:
      css_class: "bg-sky-50"

  # ══════════════════════════════════════════════════════
  # CAREER - 경력 및 역량
  # ══════════════════════════════════════════════════════
  - block: steps
    id: career
    content:
      title: 경력 및 역량
      text: 20년의 진심이 담긴 전문성으로 당신의 곁에 함께합니다.
      items:
        - title: 웰니스 컨설팅 (Wellness Consulting)
          text: 20년 경력의 웰니스 & 네트워크 마케팅 비즈니스 컨설턴트 (Amway 주력, 애터미 등). 2026 Amway 미시간 본사 투어 세미나 이수 및 지속적인 글로벌 비즈니스 파트너십 구축.
          icon: chart-bar
        - title: 전문 홈케어 (Professional Homecare)
          text: 15년 경력의 전문 홈케어 에이전트 (Eleon Healthcare Inc. 등). 공인 홈 헬스 에이드 (Certified Home Health Aide, CHHA) 자격 보유. 가장 가까이서 이웃의 일상을 돌본 진심의 경험.
          icon: home
        - title: 라이프 플래닝 (Life Planning)
          text: 공인 보험 프로듀서 및 브로커 (Insurance Producer & Broker, Ameritas 등). 미국 뉴저지 호손(Hawthorne) 및 동부 지역 중심 활동. 건강부터 재무까지 삶 전반을 케어하는 종합 라이프 플래닝.
          icon: document-text
    design:
      layout: horizontal
      marker_style: icon
      connector: none
      css_class: "bg-white"

  # ══════════════════════════════════════════════════════
  # TESTIMONIALS - 추천사 & 후기
  # ══════════════════════════════════════════════════════
  - block: testimonials
    id: testimonials
    content:
      title: 고객 추천사
      text: 20년간 함께해 온 파트너와 고객들의 진심 어린 후기입니다.
      items:
        - name: 김OO 님
          role: 비즈니스 파트너
          # avatar: team/avatar.png
          text: |
            정숙 사장님은 말씀하신 것은 어떤 일이 있어도 행동으로 지키시는 분입니다. 20년이라는 긴 시간 동안 한결같은 모습으로 곁에서 멘토링해 주신 덕분에, 저도 지치지 않고 믿음직한 비즈니스를 함께 키워올 수 있었습니다.
        - name: 이OO 님
          role: 웰니스/제품 소비자
          # avatar: team/avatar.png
          text: |
            가족 건강 때문에 뉴트리라이트와 홈 케어 제품을 상담받았는데, 제 상황을 정말 내 가족처럼 섬세하게 귀 기울여 들어주셨어요. 불필요한 권유 없이 딱 필요한 맞춤 솔루션만 정직하게 제안해 주셔서 대만족입니다.
        - name: 박OO 님
          role: 홈케어/라이프 케어 고객
          # avatar: team/avatar.png
          text: |
            뉴저지 호손 지역에서 정숙 님 모르는 분이 없을 정도로 신뢰가 두터우신 분이죠. 오랜 홈케어 경험이 있으셔서 그런지 일상 전반을 케어해 주시는 안목과 따뜻한 성실함이 늘 감동을 줍니다.
    design:
      layout: cards

  # ══════════════════════════════════════════════════════
  # FAQ - 자주 묻는 질문
  # ══════════════════════════════════════════════════════
  - block: faq
    id: faq
    content:
      title: 자주 묻는 질문
      text: 상담 전에 궁금하신 점을 먼저 확인해 보세요.
      items:
        - question: 네트워크 비즈니스나 부업이 처음인데, 초보자도 할 수 있나요?
          answer: |
            네, 당연히 가능합니다. 20년 동안 쌓아온 저만의 체계적인 교육 프로그램과 1:1 멘토링을 통해, 기초부터 탄탄하게 자립하실 수 있도록 언행일치의 자세로 끝까지 함께 발맞추어 도와드립니다.
        - question: 뉴저지 호손 지역 외에 다른 지역에서도 제품 상담이나 비즈니스 참여가 가능한가요?
          answer: |
            네, 가능합니다. 뉴저지 및 뉴욕 등 미국 동부 지역 중심의 대면 미팅은 물론, 온라인(Zoom, 디지털 도구)을 통해 전 세계 어디서든 긴밀하게 소통하며 컨설팅을 진행하고 있습니다.
        - question: 암웨이 제품 회원가입이나 구매 절차는 어떻게 되나요?
          answer: |
            본 홈페이지의 '상담 신청'을 통해 메시지를 남겨주시면, 정숙 님이 직접 확인 후 가장 쉽고 정직한 방법으로 회원가입 및 맞춤형 제품 큐레이션을 안내해 드립니다.

  # ══════════════════════════════════════════════════════
  # CTA - 상담 신청
  # ══════════════════════════════════════════════════════
  - block: cta-card
    id: contact
    content:
      title: 지금 바로 상담을 신청해 보세요
      text: 제품 문의, 비즈니스 파트너 문의, 라이프 케어 상담 — 어떤 질문이든 진심으로 답해드립니다.
      button:
        text: 카카오톡 채널 상담
        url: "#"
        icon: chat-bubble-left-right
    design:
      card:
        css_class: "bg-gradient-to-br from-sky-600 to-emerald-600 text-white"
---
