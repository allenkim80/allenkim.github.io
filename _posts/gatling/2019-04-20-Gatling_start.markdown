---
layout: post
title:  "Gatling을 이용한 Load test의 시작"
date:   2019-04-20 17:00:00
author: Allen Kim
categories: Gatling
---

오늘부터 Gatling을 이용한 Load test project를 만들어가는 포스트를 해보려고 합니다. 
Load test는 보통 Server 개발 이후 Service를 하기 이전에 구성하고자 하는 Architecture의 Performance를 확인 및 
측정을 하기 위해서 실행하는 테스트 입니다.

보통 많은 회사에서는 상용화된 Tool을 이용해서 많이 Load test를 하고 있으나, 전 Open source인 Gatling을 가지고 환경 구성을 해보고자 합니다. 

##Blog 구성

- maven 으로 구성된 Gatling project
- Docker image build 
- Docker image를 활용한 Test run
- Jenkins을 활용하여 테스트 자동화  

이러한 형태로 구성하였으나 두서없이 진행될 수도 있습니다. 

한번 시작해 보겠습니다. 