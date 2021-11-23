---
title: "우분투 내려받기"
description: "최신 버전의 우분투를 내려받아 다양한 환경에 설치하여 사용할 수 있습니다."
image: "download.svg"
backgroundType: suru #light, dark, accent, suru, suru-topped, image
ubuntuVersions:
    ltsVersion: "20.04 LTS"
    normalVersion: "21.10"
    ltsReleaseNote: https://wiki.ubuntu.com/FocalFossa/ReleaseNotes
    normalReleaseNote: https://discourse.ubuntu.com/t/impish-indri-release-notes/21951
mirrors:
   - name: 
     url: https://ftp.harukasan.org/ubuntu-releases/HEADER.html
---

# 버전 및 요구사양
## 우분투 {{< param "ubuntuVersions.ltsVersion" >}}
가장 최근 출시된 LTS(장기 지원) 버전인 우분투 {{< param "ubuntuVersions.ltsVersion" >}}는 5년간 유지보수 및 보안 업데이트가 무료로 제공됩니다.
대부분의 경우, 안정적인 사용을 위해 LTS 버전 사용이 권장됩니다.

[우분투 {{< param "ubuntuVersions.ltsVersion" >}} 릴리즈 노트 보기]({{< param "ubuntuVersions.ltsReleaseNote" >}})

## 우분투 {{< param "ubuntuVersions.normalVersion" >}}
새로운 기능을 먼저 사용해 보고 싶다면, 가장 최신 버전인 우분투 {{< param "ubuntuVersions.normalVersion" >}}를 사용해 보세요. 출시 후 9개월간 유지보수 및 보안 업데이트가 무료로 제공됩니다.

[우분투 {{< param "ubuntuVersions.normalVersion" >}} 릴리즈 노트 보기]({{< param "ubuntuVersions.normalReleaseNote" >}})

## 요구 사양

 - 최소 2GHz 듀얼 코어 프로세서와 4GB 시스템 메모리
 - 25GB 이상의 저장 장치 여유공간
 - 인터넷 연결은 있으면 좋습니다.
 - 설치 매체로 사용할 장치: DVD 드라이브, USB 디스크 등

# 내려받기

## 공식 홈페이지에서 내려받기

{{< button text="데스크탑" href="https://ubuntu.com/download/desktop" icon="begin-downloading" >}}
{{< button text="서버" href="https://ubuntu.com/download/server" icon="machines" >}}
{{< button text="Raspberry Pi" href="https://ubuntu.com/download/raspberry-pi" icon="switcher-dashboard" >}}
{{< button text="사물인터넷 (Ubuntu Core)" href="https://ubuntu.com/download/iot" icon="switcher-dashboard" >}}

## 국내 미러 서버에서 내려받기
국내 미러 서버에서 데스크탑 또는 서버용 CD/DVD 이미지를 빠르게 내려받을 수 있습니다.

{{< button text="KAIST" href="http://ftp.kaist.ac.kr/ubuntu-cd/HEADER.html" icon="begin-downloading" >}}
{{< button text="카카오 (Kakao Corp.)" href="https://mirror.kakao.com/ubuntu-releases/" icon="begin-downloading" >}}
{{< button text="LANET" href="https://ftp.lanet.kr/ubuntu-releases/" icon="begin-downloading" >}}
{{< button text="AniGil Linux Archive" href="https://mirror.anigil.com/ubuntu-cd/HEADER.html" icon="begin-downloading" >}}
{{< button text="Harukasan (부경대학교)" href="https://ftp.harukasan.org/ubuntu-releases/HEADER.html" icon="begin-downloading" >}}

## 퍼블릭 클라우드에서 사용하기
- [퍼블릭 클라우드용 이미지](http://cloud-images.ubuntu.com/)
- Amazon Web Services: [마켓플레이스](https://aws.amazon.com/marketplace/seller-profile?id=565feec9-3d43-413e-9760-c651546613f2), [문서](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/EC2_GetStarted.html)
- Microsoft Azure: [Ubuntu on Azure](https://azure.microsoft.com/ko-kr/ubuntu/#overview), [문서](https://docs.microsoft.com/ko-kr/azure/virtual-machines/linux/quick-create-portal)
- Google Cloud Platform: [마켓플레이스](https://console.cloud.google.com/marketplace/product/ubuntu-os-cloud/ubuntu-focal?project=youngbin-xyz), [문서](https://cloud.google.com/sdk/docs/quickstart-debian-ubuntu)

# WSL (Windows Subsystem for Linux)
최신 버전의 Windows 10 또는 Windows 11 을 사용 중이라면, WSL 환경으로 우분투를 편리하게 만나보실 수 있습니다.

{{< button text="WSL환경에 우분투 설치 (WSL Korea User Group 문서)" href="https://wslhub.com/wsl-firststep/firststep/install/" icon="begin-downloading" >}}