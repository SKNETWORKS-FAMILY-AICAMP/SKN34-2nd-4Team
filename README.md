<div align="center">
  <img src="./docs/image/phoenix-team-banner.png" width="100%" alt="불사조 팀 배너" />
</div>

<br />

# 1. 팀 소개

## 📌 팀명

<h1 align="center">🔥 SKN34-2nd-4Team : 불사조 🔥</h1>

<br />

## 📌 팀 멤버

<table>
  <thead>
    <tr>
      <th align="center">김건우</th>
      <th align="center">이성민</th>
      <th align="center">전진영</th>
      <th align="center">최성욱</th>
      <th align="center">황수빈</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><img src="./docs/image/4.png" width="130" alt="김건우" /></td>
      <td align="center"><img src="./docs/image/1.png" width="130" alt="이성민" /></td>
      <td align="center"><img src="./docs/image/3.png" width="130" alt="전진영" /></td>
      <td align="center"><img src="./docs/image/2.png" width="130" alt="최성욱" /></td>
      <td align="center"><img src="./docs/image/5.png" width="130" alt="황수빈" /></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/ilil1">@ilil1</a></td>
      <td align="center"><a href="https://github.com/lsm15111">@lsm15111</a></td>
      <td align="center"><a href="https://github.com/msi67811-jpg">@msi67811-jpg</a></td>
      <td align="center"><a href="https://github.com/Overlay1010">@Overlay1010</a></td>
      <td align="center"><a href="https://github.com/subinss838">@subinss838</a></td>
    </tr>
    <tr>
      <td align="center">팀원1</td>
      <td align="center"><strong>팀장</strong></td>
      <td align="center">팀원2</td>
      <td align="center"><strong>팀장</strong></td>
      <td align="center">팀원3</td>
    </tr>
  </tbody>
</table>

<br />

# 2. 프로젝트 개요

## 📌 프로젝트 명

### CardOps - 신용카드 고객 이탈 조기경보 및 고객 관리 서비스

## 📌 프로젝트 소개

CardOps는 신용카드 고객 데이터를 바탕으로 고객의 이탈 가능성을 예측하고, 예상 거래활동과 실제 거래활동의 차이를 분석해 위험 고객을 조기에 발견하는 머신러닝 기반 고객 관리 서비스입니다.

분류·회귀·군집 모델의 결과를 결합하여 고객별 이탈 위험도와 활동성 상태, 고객 유형을 제공하며, 분석 결과를 대시보드와 캠페인 업무에 연결해 부서별 의사결정을 지원합니다.

## 📌 프로젝트 필요성(배경)

- 신규 고객을 확보하는 것만큼 기존 고객의 이탈을 예방하고 관계를 유지하는 것이 중요합니다.
- 단순 이탈 여부만 예측하면 고객의 활동이 언제부터 감소했는지 파악하기 어렵습니다.
- 고객마다 연령, 신용한도, 거래 규모와 이용 패턴이 다르므로 동일한 기준으로 관리하기 어렵습니다.
- 이탈 확률, 예상 대비 거래활동, 고객군 특성을 함께 분석하면 위험 고객을 더 구체적으로 구분하고 적절한 대응 전략을 수립할 수 있습니다.
- 분석 결과를 실제 고객 관리와 캠페인 업무에 활용하려면 모델 실험에 그치지 않고 웹 서비스와 데이터베이스까지 연결된 구조가 필요합니다.

## 📌 프로젝트 목표

1. 비즈니스 문제를 이해하고 고객 이탈 방지를 위한 머신러닝 모델 활용 계획을 수립합니다.
2. 모델 학습에 필요한 데이터 정제, 탐색적 데이터 분석(EDA), 전처리 및 특징공학을 수행합니다.
3. 분류 모델로 고객별 이탈 여부와 이탈 확률을 예측합니다.
4. 회귀 모델로 고객별 예상 거래건수를 계산하고 실제 거래건수와의 차이인 활동성 갭을 산출합니다.
5. 군집 모델로 행동과 신용여력, 활동성 갭이 유사한 고객을 세분화합니다.
6. 기본 모델, 특징공학 모델, 하이퍼파라미터 탐색 결과를 비교해 과제별 최종 모델을 선정합니다.
7. React, FastAPI, TiDB Cloud를 연동해 고객 분석 결과를 조회하고 활용할 수 있는 서비스를 구현합니다.
8. GitHub와 Render를 이용해 프론트엔드와 백엔드를 배포하고, Docker Compose로 재현 가능한 로컬 개발 환경을 구성합니다.
