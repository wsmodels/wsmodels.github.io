---
layout: home
header:
  title: Experts in watershed modeling
  text: >
    HydroCore independently develops watershed models applicable at various spatial and temporal scales and applies them to research projects.
  action: # action button is optional
    label: Find Out More
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary text-white
    # background_style: bg-info text-white
    title: Watershed Modeling
    text: 유역모델은 유역 내에서 발생하는 다양한 수문현상과 이와 연관된 오염물질 거동 양상을 수학적으로 표현한 컴퓨터 모의 도구입니다. 유역모델을 이용하여 유역에서 일어나는 수문현상과 오염부하의 시공간적 분포 특성을 이해할 수 있으며, 이를 통해 환경 변화에 따른 장래 변동성 예측과 관리 방안의 효과를 과학적으로 분석할 수 있습니다.
    actions:
      - title: Get Started!
        url: '#page-top'
        class: btn-light

  - type: models.html
    section_id: models
    title: Our Watershed Models!
    background_style: bg-info text-black
    models:
      - title: CAMEL
        text: 분포형 모델, 소유역 상세 모의
        image: assets/img/services/camel.jpg
        url: https://hydrocore.github.io/CAMEL/
      - title: STREAM
        text: 격자기반 복합형 모델, 중대형 유역 모의
        image: assets/img/services/stream.jpg
        url: https://hydrocore.github.io/STREAM/
      - title: SNIPE
        text: 전국규모 평가 모델, 전국 관리방안 도출
        image: assets/img/services/snipe.jpg
        url: https://hydrocore.github.io/SNIPE/
      - title: REDPOLL
        text: 중급 개략평가 모델, 원단위 평가 대체 모델
        image: assets/img/services/redpoll.jpg
        url: https://hydrocore.github.io/REDPOLL/
      - title: ANNE
        text: 앙상블 강우유출, 인공신경망 모델
        image: assets/img/services/redpoll.jpg
        url: https://hydrocore.github.io/
      - title: WRF-Hydro-WQ
        text: WRF-Hydro 기반 수문, 수질 모의 모델
        image: assets/img/services/redpoll.jpg
        url: https://hydrocore.github.io/

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: Services
    services:
      - title: Diffuse Pollution Modeling
        text: 유역모델링(Watershed Modeling)은 유역 내에서 일어나는 수문 및 비점오염 현상을 과정별로 이해하고, 그 시공간적 분포를 파악하며, 기후나 토지이용 등 환경변화의 결과를 예측하기 위한 매우 유력한 수단입니다. 하이드로코어는 국내외에서 널리 이용되고 있는 SWAT, HSPF, SWMM 등의 유역모델은 물론, 우리나라의 환경특성에 적합한 CAMEL, STREAM 등 분포형 유역모델을 독자적으로 개발하고 적용하는 국내 최고의 유역모델링 기술을 보유하고 있습니다.
        icon: bi-gem text-info
        # url: https://hydrocore.github.io/CAMEL/
      - title:  Diffuse Pollution Monitoring
        text: 유역의 주요 수문 및 수질 현상은 상호 유기적으로 연결된 지형, 토양, 지질, 식생, 토지이용 등 환경요소와 기상 현상에 의해 결정됩니다. 따라서, 유역에서의 비점오염 현상을 이해하고 문제점을 파악하기 위해서는 유역환경에 대한 조사분석이 반드시 필요합니다. 하이드로코어는 각종 환경요소에 대한 다양한 현장조사 경험을 바탕으로 최고 수준의 맞춤형 모니터링 서비스를 제공합니다.
        icon: bi-rocket-takeoff
        # url: https://hydrocore.github.io/STREAM/
      - title: Diffuse Pollution Controls 
        text: 하이드로코어는 관심 유역을 대상으로 유역환경 조사·분석 및 모니터링, 유역/하천 모델링 기법을 바탕으로 하여 구조적·비구조적 비점오염 저감방안의 설치 및 운영에 대한 타당성을 조사·분석하고, 기본계획을 수립하는 서비스를 제공합니다
        icon: bi-activity
        # url: https://hydrocore.github.io/SNIPE/
      - title: Mini-UAV Photogammetry
        text: 자동항법장치를 장착한 무인항공기(UAV, Unmanned Aerial Vehicle)는 근래에 들어 급속하게 발전하고 있는 기술분야로서, 이를 이용한 항공사진촬영과 영상분석을 통해 고해상도 토지피복도와 수치고도자료(DEM)를 용이하게 획득할 수 있습니다. 하이드로코어는 자동항법장치를 장착한 소형 무인항공기를 이용하여 유역과 하천에 대한 공간정보를 신속하게 획득하고 분석하며, 영상 데이타베이스를 구축하는 최첨단 서비스를 제공합니다.
        icon: bi-heart-fill
        # url: https://hydrocore.github.io/REDPOLL/
      - title: GIS 
        text: GIS Analysis
        icon: bi-emoji-heart-eyes
        # url: https://hydrocore.github.io/
      - title: Big Data Analysis
        text: Big Data Analysis
        icon: bi-emoji-sunglasses-fill
        # url: https://hydrocore.github.io/

  # - type: portfolio.html
  #   # this section has always ID 'portfolio'
  #   #section_id: portfolio
  #   #background_style: bg-dark
  #   projects:
  #     - title: Project 1
  #       text: This is a very short project description.
  #       # the images are located in:
  #       # img/portfolio/fullsize
  #       # img/portfolio/thumbnails
  #       icon: 1.jpg
  #       url: '#'
  #     - title: Project 2
  #       text: This is a very short project description.
  #       icon: 2.jpg
  #       url: '#'
  #     - title: Project 3
  #       text: This is a very short project description.
  #       icon: 3.jpg
  #       url: '#'
  #     - title: Project 4
  #       text: This is a very short project description.
  #       icon: 4.jpg
  #       url: '#'
  #     - title: Project 5
  #       text: This is a very short project description.
  #       icon: 5.jpg
  #       url: '#'
  #     - title: Project 6
  #       text: This is a very short project description.
  #       icon: 6.jpg
  #       url: '#'

  - type: aside.html
    section_id: aside
    title: HydroCore introduction document 
    actions:
      - title: Download Now!
        url: assets/downloads/HC.pdf
        class: btn-light

  - type: timeline.html
    section_id: timeline
    title: Major Achievements!
    background_style: bg-dark text-primary
    last_image: assets/img/timeline-end.png
    actions:
      - image: assets/img/portfolio/thumbnails/1.jpg
        title: >+
          2017-2018
          **Humble Beginnings**
        text: >-
          We begun with small group of people willing to work hard and make our
          teaching skills worth , in front of all others!
      - image: assets/img/portfolio/thumbnails/2.jpg
        title: >+
          November 2019
          An Coaching started
        text: >-
          We started to gather like minded people and started our stategies
          and future plans to them. As a result , interested people joined us!

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: 02-2627-3570
      icon: bi-telephone-fill
    - title: E-Mail
      icon: bi-envelope-fill
      url: mailto:admin@hydrocore.co.kr
    - title: Twitter
      icon: bi-twitter
      url: '#'
    - title: Facebook
      icon: bi-facebook
      url: '#'

---
