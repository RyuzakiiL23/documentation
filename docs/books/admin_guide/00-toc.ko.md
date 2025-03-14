---
title: Rocky와 함께 Linux를 배우기
---

# Rocky와 함께 Linux를 배우기

관리자 설명서는 시스템 관리자에 초점을 맞춘 교육 문서입니다. 이 설명서는 미래의 시스템 관리자, 업데이트/교체를 원하는 현재의 시스템 관리자, 또는 Linux 환경, 명령어, 프로세스 등에 대해 더 자세히 알고 싶어하는 Linux 사용자가 사용할 수 있습니다. 다른 모든 문서들과 마찬가지로, 시간이 지남에 따라 업데이트될 것 입니다.

먼저 Linux 소개로 시작하겠습니다. 이 소개에서는 Linux, 배포 및 운영 체제를 둘러싼 전체 에코시스템에 대해 설명합니다.

User Commands는 Linux를 빠르게 습득하기 위한 필수 명령어들이 포함되어 있습니다. 경험이 많은 사용자는 고급 Linux 명령어에 대한 내용의 문서도 참조해야 합니다.

다음은 VI 텍스트 편집기에 관한 내용입니다. Linux에는 많은 편집기가 제공되지만, VI는 가장 강력한 편집기 중 하나입니다. 다른 명령어들은 때때로 VI 명령어들과 동일한 구문을 사용합니다. (예:`sed`) 따라서 VI에 대해 알고 있거나, 최소한의 필수 기능(파일 열기, 저장, 종료 또는 저장하지 않고 종료)을 명확히 이해하는 것은 매우 중요합니다. 사용자는VI 편집기를 사용하면서 다른 기능들에 대해 더욱 익숙해질 것 입니다. 다른 대안은 Rocky Linux에 기본적으로 설치되는 nano를 사용하는 것 입니다. 다양한 용도로 사용할 수는 없지만, 사용하기 쉽고 간단하며 작업을 수행할 수 있습니다.

그런 다음 Linux의 심층적인 기능을 통해 시스템이 다음을 해결하는 방법을 확인할 수 있습니다:

* 사용자 관리
* 파일 시스템
* 프로세스 관리

백업 및 복원은 시스템 관리자에게 필수적인 정보입니다. 리눅스에는 백업 기능을 향상시키는 많은 소프트웨어 솔루션(rsnapshot, lsyncd 등)이 함께 제공됩니다. 그렇기 때문에 운영 체제 내에 존재하는 백업의 필수 구성 요소를 아는 것은 중요합니다. 이 문서에서는 두 가지 도구에 대해 알아볼 것 입니다: 1) `tar`, 2) 많이 사용 하지 않는 `cpio`

Systemd가 등장한 이후 몇 년 동안 부팅 프로세스 중 시스템 관리가 크게 발전했기 때문에 System Startup도 중요하게 읽어야 하는 문서입니다.


마지막 문서에서는 작업 관리, 네트워크 구현 및 설치를 포함한 소프트웨어 관리에 대해 설명합니다.

