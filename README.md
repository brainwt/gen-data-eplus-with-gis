# Di-eg
***D***ata handing ***i***nfrastructure for ***e***Plus and ***g***IS

```
(240828) 드래프트 버전입니다. 24년 말, 25년 초 공식 업데이트가 있을 예정입니다.          
```

## 사용법
- n/a

## 배경
- GIS 데이터는 널리사용되는 공통기반 데이터 입니다. 
- 또한 EnergyPlus는 미국 DOE에서 2000년초 부터 개발 및 현재까지 유지관리되는 첨단 건물에너지 성능 분석 엔진입니다.
- 다만, GIS 데이터와 EnergyPlus를 결합하여 건물에너지 성능 분석하는 작업은 상당히 까다롭습니다.
- 우선, 지리정보시스템과 건물에너지해석 이라는 영역에 대한 상당한 이해가 필요합니다.
- 이러한 이해를 바탕으로, 이질적 데이터를 자유롭게 처리할 수 있는 컴퓨터 프로그래밍 스킬 또한 필요합니다.
- 결론적으로 진입장벽이 높고 돈도 안되기 때문에 .... 파편적, 일회성으로만 분석되기 마련입니다.

- 따라서, Di-eg는 GIS 데이터와 Eplus 엔진을 기반하여,
- 국내 전지역에 대해 "데이터 수집-처리-분석"의 파이프라인을 구축하여 전국DB 생성을 자동화하려는 목적을 갖고 있습니다.

## Di-eg로 부터 생성되는 정보
- GIS 데이터와 EnergyPlus 엔진을 결합하여 건물(군) 단위 음영, 일사, 부하 등의 데이터를 생성합니다.
- 현시점에서는 테이블 정의서만 수록합니다.

## 주의사항
- **개발중** 입니다. 

## Releases 
- 23년07월: 설계 완료
- 24년08월: 서울 분석 완료
- 24년08월: 데이터 테이블 정의서 공개
- 24년12월: 경기도 분석 예정
- 25년: 전국 분석 예정

## 출처
- 출처 표기  
  - 국문: 건물부문 탄소중립 가속화를 위한 건물에너지 소비 데이터 통합관리 기반기술 개발 (과제번호 : RS-2023-00244769)  
  - 영문: Grant RS-2023-00244769, Development of a data framework for integrating building energy datasets and applications to accelerate carbon neutrality in the building sector

## 관련 참고문헌
- 이동혁, 김덕우. (2024). 건물 음영 지표 개발용 데이터베이스 구축을 위한 GIS 기반 도시 단위 EnergyPlus 시뮬레이션 . 한국건축친환경설비학회 논문집, 18(2), 85-97.

## 관련 참고자료
- 김덕우, 김혜기 (2024). 도로명주소 건물DB 활용성 검토, 01월 24일, 한국건설기술연구원
- https://docs.google.com/presentation/d/1_H79wQc_MlXx908cCVUAWOryKr-0owfHbpyNxUC6EVY/edit?usp=sharing

---
# Funding

Research was conducted under the KICT Research Program (project no. 20220260-001, Data-Centric Checkup Technique of Building Energy Performance) funded by the
Ministry of Science and ICT.

This work is supported by the Korea Agency for Infrastructure Technology Advancement(KAIA) grant funded by the Ministry of Land, Infrastructure and Transport (Grant RS-2023-00244769, Development of a data framework for integrating building energy datasets and applications to accelerate carbon neutrality in the building sector)

---
   
# Copyright
***D***ata handing ***i***nfrastructure for ***e***Plus and ***g***IS in South Korea Copyright (c) 2023
Korea Institute of Civil Engineering and Building Technology, KICT (subject to receipt of any required approvals from South Korea Ministry of Land, Infrastructure and Transport, MOLIT). All rights reserved.

If you have questions about your rights to use or distribute this software, please contact KICT at deukwookim@kict.re.kr.

NOTICE. This softwarre was developed under funding from the MOLIT South Korea Government consequently retains certain rights. As such, the South Korea Government has been granted for itself and others acting on its behalf a paid-up, nonexclusive, irrevocable, worldwide license in the code to reproduce, distribute copies to the public, prepare derivative works, and perform publicly and display publicly, and to permit other to do so.

끝.
