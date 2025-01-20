# MESCADAS - 지능형 스마트 팩토리 


# MESCADAS 소개
**MESCADAS**는 *지능형 스마트 팩토리 시스템 개발* 팀프로젝트로서 다음 세가지의 컨셉이 통합된 전체 시스템을 아우릅니다(이하 `MSD`):

- MES : 생산공정관리와 공정 데이터 분석을 통한 생산성/품질 향상
  - 생산 스케줄링, 자재관리, 품질관리, 생산 이력 추적
- SCADA: 현장의 설비와 장비 실시간 모니터링 및 제어
- DAS : 데이터 수집 시스템

MSD는 닷넷(C# .NET) 코드로 개발된 여러 소프트웨어로 이러우진 통합 시스템입니다.

서버, 클라이언트, HMI 소프트웨어, AI 비전검사기가 Restful API 및 TCP 소켓 및 필드버스 네트워크 통신을 통해 서로 소통합니다.

 닷넷 코어로 개발된 서버 애플리케이션, **MSD Crux 프로젝트**([Github](https://github.com/KyleOpenGit/Msd-Crux-repo))는 Headless Architecture로 이루어져 PC, Mac, Web, Mobile등 다양한 클라이언트 개발에 대응할 수 있는 기반이 갖추어져있으며 확장성이 높은 Application Architecture로 구성되었습니다. 



# 기타
본 Git 레포지토리는 MESCADAS 시스템의 문서페이지 사이트를 생성하는 관리 레포지토리입니다. [DocFX](/repo-docs/DocFx.md)에 관한 내용을 참고해주세요.