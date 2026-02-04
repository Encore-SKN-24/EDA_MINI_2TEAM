# SKN24-EDA_MINI_2TEAM
## 🧀시골쥐들의 서울내기🐭
*"서울시 전세사기 위험 지표"*

## 1. 팀 소개

## 1-1.팀명
### 🧀시골쥐들🐭

## 1-2. 팀원
|   이름   | GitHub            | 업무 |
|:--------:|:-----------------:| :---:|
| 권민세 | [KweonMinSe0109](https://github.com/KweonMinSe0109) | 기획, 데이터 수집 및 전처리, 차트 시각화, Readme 작성  |
| 김정현 | [Jeich-16](https://github.com/Jeich-16) | 기획, 데이터 수집 및 전처리, 차트 시각화, Readme 작성
| 박영훈 | [aprkaos56](https://github.com/aprkaos56) | 기획, 데이터 수집 및 전처리, 차트 시각화, Readme 작성
| 황인규 | [hwang-in-kyu](https://github.com/hwang-in-kyu) |  기획, 데이터 수집 및 전처리, 차트 시각화, Readme 작성  |

---

## 2. 📋 프로젝트 개요
<img width="805" height="821" alt="image" src="https://github.com/user-attachments/assets/b5732ffc-5c08-4462-a309-9d6532e0e6d0" />

자료: https://housinginfo.seoul.go.kr/hmpg/homa/trou/homaDetail.do


> 본 프로젝트는 공공 데이터 분석을 통해 서울시 행정동별 전세사기 위험도를 측정하고, 시각화된 지표를 통해 사용자에게 직관적인 위험 정보를 제공하는 것을 목적으로 합니다.

## 2-1. 프로젝트 소개
> 본 프로젝트는 '서울 지역 자취 및 독립을 희망하는 대학생/사회초년생들의 현실적인 고민'에서 출발했습니다. 저희 조뿐만 아니라, 수강생 대다수를 포함한 청년 세대에게 서울은 꿈의 무대인 동시에, 전세사기라는 거대한 사회적 위험이 도사리는 불안한 공간이기도 합니다. 정보 비대칭성이 심각한 부동산 시장에서, 경험이 부족한 임차인이 스스로를 보호하기에는 기존 시스템의 한계가 명확합니다.
우리는 이러한 사회적 난제를 해결하기 위해, 단순한 정보 나열이 아닌 데이터 기반의 객관적 안내판을 구축하고자 합니다. 흩어져 있는 공공 데이터를 통합하고 이를 시각화하여, 전세 계약 전 반드시 확인해야 할 위험 인자를 도출합니다.

## 2-1. 🖼️ 프로젝트 필요성(배경)
#### 사회적 문제 심화:
>  깡통전세 및 전세사기 피해가 여전히 발생하고 있으며, 청년층과 서민층의 주거 불안정이 심화되고 있습니다.
#### <img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/e56a9aa3-c1a3-4b50-aacb-23f68025671e" />
#### 출처: https://imnews.imbc.com/news/2025/econo/article/6781511_36737.html

#### 정보의 비대칭성:
>  임대인과 임차인 사이의 정보 불균형으로 인해, 일반 시민이 계약 전 해당 매물의 위험성을 객관적으로 파악하기 어렵습니다.
#### 사후 처리가 아닌 사전 예방 필요:
>  사고 발생 후의 대처보다, 공공 데이터를 활용한 선제적 위험 감지 시스템이 절실한 시점입니다.

---

## 2-2. 🎯 프로젝트 목표
#### 데이터 통합 분석:
 > 실거래가, 전세가율, 해당 동 평균 전세가 등 흩어져 있는 데이터를 하나로 통합합니다.
  
#### 핵심 위험 인자 도출:
 > 데이터 통합 분석으로 얻은 정보를 활용하여 실제 사기에 가장 큰 영향을 미치는 요인이 무엇인지 통계적으로 밝혀내는 것입니다.
  
#### 시각화 기반 정보 제공:
 > 2025년 서울시 전세가율을 분석하여, 사용자가 계약하기 전 위험 매물을 한눈에 식별할 수 있도록 시각화합니다.

---

## 3. 🧰 기술 스택
| 분류                 | 기술/도구                                                                 |
|----------------------|------------------------------------------------------------------------------|
| 언어          |![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)                                                        |
| 라이브러리   | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4479A1?style=for-the-badge&logo=python&logoColor=white)                                                        |
| 협업 툴       | ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)                                                   |                                                |

---

## 4. ✅ 데이터 출처
> 서울특별시 자치구별 전세사기 발생건수 (https://data.seoul.go.kr/dataList/OA-22867/F/1/datasetView.do)

> 서울특별시 실거래가/전월세가 공개시스템 (https://rt.molit.go.kr/pt/xls/xls.do?&mobileAt=) 

---

## 5. ✅ 데이터 전처리
#### 1. 각 컬럼 별 값 확인
#### <img width="1295" height="603" alt="image" src="https://github.com/user-attachments/assets/a14ffc8a-c3e6-4607-92c3-6b387f8d409a" />


#### 2. 결측치 비율 확인
#### <img width="667" height="841" alt="image" src="https://github.com/user-attachments/assets/64c90a03-9ea4-4abe-9d81-e7a42b8c6fcc" />


#### 3. 이상치 도출
#### <img width="1422" height="587" alt="image" src="https://github.com/user-attachments/assets/152f9721-1ce6-46e3-9db6-8a7c3651667f" />


#### 4. 피처 엔지니어링(Feature Engineering) 과정 
#### <img width="1170" height="558" alt="image" src="https://github.com/user-attachments/assets/4afd6f92-c6c5-4c80-b7d4-225b8854c553" />
#### <img width="896" height="631" alt="image" src="https://github.com/user-attachments/assets/d5e0541a-7a7b-4985-af4e-e9590354914c" />


#### 5. 전처리 결과
#### <img width="1496" height="338" alt="image" src="https://github.com/user-attachments/assets/d34eeab6-a893-4c79-95f1-a58d692b1552" />

---

## 6. 📊 시각화 자료


#### 1. 2025년 서울특별시 자치구 별 전세 계약 건수 
#### <img width="1473" height="642" alt="image" src="https://github.com/user-attachments/assets/83c32b99-c42a-4bf9-9172-44546165ddd6" />


#### 2. 2025년 서울시 월별 전세 계약 건수
#### <img width="1472" height="632" alt="image" src="https://github.com/user-attachments/assets/87509787-b3c8-4b00-8667-efa3a4c4e219" />


#### 3. 위험요소 컬럼 선정 기준
#### <img width="1131" height="542" alt="image" src="https://github.com/user-attachments/assets/33fd3b09-61c5-44c4-af52-1866fb34e541" />


#### 4-1. 전세가율 구간 별 건물나이 구성비
#### <img width="1226" height="482" alt="image" src="https://github.com/user-attachments/assets/f71412b7-17c4-4084-a1e6-3e2407c9a762" />


#### 4-2. 전세가율 구간 별 주택유형 구성비
#### <img width="1230" height="483" alt="image" src="https://github.com/user-attachments/assets/929d3639-234d-47f1-a2cc-e980525c15c2" />


#### 5. 송파구 동별 평균 전세가율
#### <img width="1220" height="725" alt="image" src="https://github.com/user-attachments/assets/5af8277c-8235-4e97-952c-40bf16ea6c4b" />


#### 6. 전세가율 구간 별 평균 보증금 상대비
#### <img width="848" height="480" alt="image" src="https://github.com/user-attachments/assets/48bcbcca-b159-4664-a55c-701e9f2df858" />



## 7. ℹ️ 인사이트 도출 
> 분석 결과, 동·주택유형 평균 대비 전세가율이 높은 매물일수록 전세사기 위험군에 포함될 가능성이 크게 증가하는 경향을 확인하였습니다. 특히 연립다세대·오피스텔에서 고위험 구간 비중이 높게 나타났으며, 이는 실거래가 대비 과도한 보증금 책정이 주요 위험 신호로 작용함을 시사합니다. 또한 단순 절대 가격보다 지역 평균 대비 상대비 지표가 위험 탐지에 더욱 효과적임을 확인하였습니다. 이를 통해 전세 계약 전, ‘보증금·실거래가·주택 유형 등’의 복합적 검토가 필수적인 의사결정 요소임을 도출하였습니다.


---


## 8. 💭 한 줄 회고
### - 권민세: 
 전처리 과정에서 필요한 칼럼을 단순히 추출하는 데 그치지 않고, 결측값을 확인하고 처리하며 여러 칼럼 간 연산을 통해 새로운 지표를 생성해 보는 경험을 할 수 있어 뜻깊었습니다. 전세가율 구간별로 주택 유형과 건물 나이를 비교하는 과정에서는 예상처럼 시각화 결과가 바로 나타나지 않아 위험 기준을 설정하는 데 어려움을 겪었지만, 여러 기준을 계속 적용해 보며 이를 해결할 수 있었습니다. 앞으로는 기준 설정 단계에서 데이터 분포를 더 자세히 검토해 봐야겠다고 생각했습니다.
  
### - 김정현:
  저희 조는 개인 파트를 전담하는 방식이 아닌, 기획부터 README 작성까지 전 과정에 팀원 전원이 함께 참여했습니다. 덕분에 실시간으로 의견을 교환하며 최선의 의사결정을 내릴 수 있었고, 프로젝트 전체의 맥락을 모든 팀원이 깊이 있게 공유할 수 있었습니다.
  다만, 데이터셋 내 컬럼 간의 유기적인 관계를 분석하는 과정에서 해당 도메인에 대한 이해도가 낮아 분석의 깊이를 더하는 데 한계를 느꼈습니다. 'A 컬럼의 값이 늘어나면 B 컬럼의 값도 늘어날 것이다'라는 막연한 추측 대신, 뉴스 기사나 보고서 등을 참고해 근거 있는 가설을 세우겠습니다. 이를 통해 데이터만 바라보는 좁은 시야에서 벗어나, 전체적인 흐름을 읽을 수 있도록 하겠습니다.
### - 박영훈:
 구성원 모두가 공감할 수 있는 주제를 선정해 프로젝트를 진행함으로써, 더욱 높은 몰입도와 책임감을 가질 수 있었습니다. 또한, 공공 데이터를 활용해 막연했던 전세 위험을 시각화하고 객관적인 지표로 표현할 수 있는 과정에서 실제 의사결정에 도움이 되는 데이터 분석의 가치를 체감할 수 있었습니다. 이번 미니 프로젝트는 실 수요자의 기대치를 충족시키며, 데이터를 통해 사회 문제 해결에 직접적인 기여를 할 수 있음을 배운 의미 있는 경험이었습니다. 추후에도 다양한 데이터셋을 활용하여 다각화된 프로젝트를 진행해보면 좋을 것 같다는 생각이 들었습니다.
  
### - 황인규:
본 프로젝트를 통해 전세 위험을 단순 수치가 아닌 지역·주택유형별 상대적 지표로도 해석할 수 있다는 점을 알 수 있었습니다. 부동산 데이터의 이상치는 제거 대상이 아니라, 오히려 위험 신호로서 의미를 가질 수 있음을 분석 과정에서 확인하였습니다. 또한 흩어진 공공 데이터를 정제·통합하고 기준을 정의하는 과정이 모델 성능만큼 중요한 분석 단계임을 체감했습니다. 데이터 분석이 청년 주거 문제와 같은 현실적인 사회 문제 해결에 기여할 수 있음을 느낀 프로젝트였습니다.


