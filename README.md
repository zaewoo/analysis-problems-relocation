<h1 align="center">Analysis of Problems Caused by The Relocation.</h1>

<div align="Right">
    진행 기간: 2022.07.12. - 2022.07.15.
    </br>
    </br>
    작성 일자: 2022.07.12.
    </br>
    수정 일자: 2022.08.16.
    </br>
    </br>
    박덕용 
    </br>
    한선아
    </br>
    박재우
</div>

## 1. 서론
대통령의 집무실 이전으로 발생하게 될 문제가 화두입니다. 그 중에서도 대통령의 출근으로 통제될 도로의 체증에 관한 문제가 가장 큰 문제로 거론되고 있습니다. 저희는 이 문제가 발생하고 있는지, 즉 사실 여부를 확인하기 위해 [서울 열린데이터광장](https://data.seoul.go.kr), 그리고 [서울시 교통정보 시스템](https://topis.seoul.go.kr)에서 제공하는 서울시 교통정보 데이터를 분석하였습니다. 

### 1.1. 가정
이 분석에서는 제기된 문제, 즉 대통령의 출근으로 통제될 도로의 체증에 관한 문제가 발생하고 있다는 사실을 옳다고 가정하였습니다. 

## 2. 본론: 데이터
다음은 데이터에 관한 내용입니다.

### 2.1. 내용
[서울 열린데이터광장](https://data.seoul.go.kr), 그리고 [서울시 교통정보 시스템](https://topis.seoul.go.kr)에서 제공하는 서울시 교통정보 데이터를 이용하였습니다.

#### 2.1.1. 지점별 일자별 교통량
- 이 데이터는 주요간선도로 및 도시고속도로를 단위 시간 동안 통과하는 차량의 수를 확인할 수 있습니다. 이 데이터에서 반포대교를 포함한 인근 대교의 도로 교통량을 확인하였습니다. 
- 이 데이터에 대한 분석은 위의 가정이 옳다고 하였으므로 기준 일자보다 도로의 한 지점, 또는 단면을 단위 시간 동안 통과하는 차량의 수가 감소하여야 합니다.

#### 2.1.2. 도로별 일자별 통행 속도
- 이 데이터는 주요간선도로 및 도시고속도로를 단위 시간 동안 통과하는 차량의 속도를 확인할 수 있습니다. 이 데이터에서 반포대교를 포함한 인근 대교를 통과하는 차량의 속도를 확인하였습니다. 
- 이 데이터에 대한 분석은 위의 가정이 옳다고 하였으므로 기준 일자보다 도로의 한 지점, 또는 단면을 단위 시간 동안 통과하는 차량의 속도가 감소하여야 합니다.

### 2.2. 일자
대통령이 정식적으로 대통령 집무실로 출근한 일자는 5월 11일입니다. 이는 앞으로의 분석에서 사용될 기준 일자입니다. 아래의 분석에서는 기준 일자 이전, 즉 대통령 취임 이전, 그리고 기준 일자 이후, 즉 대통령 취임 이후로 구분하고 분석하였습니다. 기준 일자 이전은 4월 20일부터 5월 10일까지입니다. 기준 일자 이후는 5월 11일부터 5월 30일까지입니다. 이들 기간은 모두 주말, 그리고 공휴일을 제외한 기간입니다.

### 2.3. 시각
대통령이 대통령 집무실로 출근하는 시각은 9시부터 10시입니다. 이는 앞으로의 분석에서 사용될 기준 시각입니다. 아래의 분석에서는 기준 시각 이전, 즉 대통령 출근 이전, 그리고 기준 일자 이후, 즉 대통령 출근 이후로 구분하고 분석하였습니다. 기준 시각 이전은 8시부터 9시까지입니다. 기준 시각 이후는 10시부터 11시입니다.

### 2.4. 경로
대통령이 대통령 집무실로 이동하기 위해 반드시 거쳐가야 하는 대교는 다음으로 보았습니다.

- 한남대교
- 반포대교
- 한강대교
- 한남대교
- 잠수교

대통령의 자택에서 가장 가까운 대교는 반포대교입니다. 그러므로 이 분석은 반포대교를 중심으로 하였습니다. 그리고 반포대교 인근 대교도 대통령의 출근으로 인한 영향이 미쳤을 것으로 보았습니다. 그러므로 이 분석에는 반포대교를 포함한 총 다섯 개의 대교를 분석하였습니다. 

## 3. 본론: 분석
다음은 데이터를 분석한 결과에 관한 내용입니다.

### 3.1. 통행 차량의 수
첫 번째 데이터는 반포대교를 포함한 인근 대교를 지나가는 차량의 수입니다. 이 분석에서는 위의 가정이 옳다고 하였으므로 기준 일자보다 통행 차량의 수가 감소하여야 합니다. 이 분석은 기준 일자 이전, 그리고 기전 일자 이후로 분석하였습니다. 기준 시각은 9시에서 10시입니다.

#### 3.1.1. 전체 데이터 
기준 일자 이전 전체 5개 소의 평균 통행 차량 수는 2,643대입니다. 기준 일자 이후 전체 5개 소의 평균 통행 차량 수는 2,667대입니다. 결과적으로 전체 기간 동안 전체 5개 소의 평균 통행 차량 수는 24대(약 0.9%)만큼 소폭 증가하였습니다.

#### 3.1.2. 한강대교
기준 일자 이전 한강대교의 평균 통행 차량 수는 2,966대입니다. 기준 일자 이후 전체 한강대교의 평균 통행 차량 수는 2,994대입니다. 결과적으로 전체 기간 동안 한강대교의 평균 통행 차량 수는 28대(약 1.0%)만큼 소폭 증가하였습니다.

#### 3.1.3. 동작대교
기준 일자 이전 동작대교의 평균 통행 차량 수는 1,604대입니다. 기준 일자 이후 전체 동작대교의 평균 통행 차량 수는 1,701대입니다. 결과적으로 전체 기간 동안 동작대교의 평균 통행 차량 수는 97대(약 5.7%)만큼 증가하였습니다.

#### 3.1.4. 반포대교
기준 일자 이전 반포대교의 평균 통행 차량 수는 3,137대입니다. 기준 일자 이후 전체 반포대교의 평균 통행 차량 수는 3,218대입니다. 결과적으로 전체 기간 동안 반포대교의 평균 통행 차량 수는 81대(약 2.5%)만큼 소폭 증가하였습니다.

#### 3.1.5. 한남대교
기준 일자 이전 한남대교의 평균 통행 차량 수는 4,949대입니다. 기준 일자 이후 전체 한남대교의 평균 통행 차량 수는 5,063대입니다. 결과적으로 전체 기간 동안 한남대교의 평균 통행 차량 수는 114대(약 2.2%)만큼 소폭 증가하였습니다.

#### 3.1.6. 잠수교
기준 일자 이전 잠수교의 평균 통행 차량 수는 432대입니다. 기준 일자 이후 전체 잠수교의 평균 통행 차량 수는 441대입니다. 결과적으로 전체 기간 동안 잠수교의 평균 통행 차량 수는 9대(약 2.0%)만큼 소폭 증가하였습니다.

#### 3.1.7. 결과
반포대교를 포함한 인근 대교를 지나가는 차량의 수를 살펴보았습니다. 전체적으로 평균 통행 차량의 수는 소폭 증가하였습니다. 이의 명확한 원인은 찾기 어려우나 사회적 거리두기 해제로 인한 영향으로 해석하였습니다. 이 분석으로 대통령 취임 이전, 그리고 이후의 변화가 미미하다는 사실을 확인하였습니다.

### 3.2. 통행 차량의 속도
두 번째 데이터는 반포대교를 포함한 인근 대교를 지나가는 차량의 속도입니다. 이 분석에서는 위의 가정이 옳다고 하였으므로 기준 일자보다 통행 차량의 속도가 감소하여야 합니다. 이 분석은 기준 일자 이전, 그리고 기전 일자 이후로 분석하였습니다. 기준 시각은 9시에서 10시입니다. 추가적으로 이 데이터는 잠수교를 포함하고 있지 않습니다. 그러므로 데이터에 대한 분석은 잠수교를 제외한 데이터, 즉 한강대교, 동작대교, 반포대교, 그리고 한남대교에 대한 분석입니다.

#### 3.2.1. 전체 데이터 
기준 일자 이전 전체 4개 소 통행 차량의 평균 속도는 34.84km/h입니다. 기준 일자 이후 전체 4개 소 통행 차량의 평균 속도는 35.15km/h입니다. 결과적으로 전체 기간 동안 전체 4개 소 통행 차량의 평균 속도 차는 0.3km/h(약 0.8%)로 소폭 증가하였습니다.

#### 3.2.2. 한강대교
기준 일자 이전 한강대교 통행 차량의 평균 속도는 14.71km/h입니다. 기준 일자 이후 전체 한강대교 통행 차량의 평균 속도는 13.59km/h입니다. 결과적으로 전체 기간 동안 한강대교 통행 차량의 평균 속도 차는 1.12km/h(약 8.2%)로 감소하였습니다.

#### 3.2.3. 동작대교
기준 일자 이전 동작대교 통행 차량의 평균 속도는 56.82km/h입니다. 기준 일자 이후 전체 동작대교 통행 차량의 평균 속도는 60.33km/h입니다. 결과적으로 전체 기간 동안 동작대교 통행 차량의 평균 속도 차는 3.51km/h(약 5.8%)로 소폭 증가하였습니다.

#### 3.2.4. 반포대교
기준 일자 이전 반포대교 통행 차량의 평균 속도는 46.37km/h입니다. 기준 일자 이후 전체 반포대교 통행 차량의 평균 속도는 46.91km/h입니다. 결과적으로 전체 기간 동안 반포대교 통행 차량의 평균 속도 차는 0.54km/h(약 1.2%)로 소폭 증가하였습니다.

#### 3.2.5. 한남대교
기준 일자 이전 한남대교 통행 차량 평균 속도는 21.45km/h입니다. 기준 일자 이후 전체 한남대교 통행 차량의 평균 속도는 19.77km/h입니다. 결과적으로 전체 기간 동안 한남대교 통행 차량의 평균 속도 차는 1.68km/h(약 8.5%)로 감소하였습니다.

#### 3.2.6. 결과
반포대교를 포함한 인근 대교를 지나가는 차량의 속도를 살펴보았습니다. 전체적으로 평균 통행 차량의 속도는 소폭 증가하였습니다. 반포대교, 그리고 동작대교는 통행 차량의 평균 속도는 소폭 증가하였습니다. 이는 이전보다 차량 소통이 원활하다는 사실을 의미합니다. 한강대교, 그리고 한남대교는 통행 차량의 평균 속도는 감소하였습니다. 이는 이전보다 차량 소통이 원활하지 않다는 사실을 의미합니다. 이의 명확한 원인은 찾기 어려우나 사회적 거리두기 해제로 인한 영향으로 해석하였습니다. 이 분석으로 대통령 취임 이전, 그리고 이후의 변화가 미미하다는 사실을 확인하였습니다. 

## 4. 결론
이 분석에서는 제기된 문제, 즉 대통령이 집무실을 이전하였기 때문에 교통 체증이 발생하고 있다는 사실을 옳다고 가정하였습니다. 그리고 이 가정이 옳다는 근거를 마련하기 위해 다음의 데이터를 분석하였습니다. 

### 4.1. 통행 차량의 수
먼저 반포대교를 포함한 인근 대교를 지나가는 차량의 수를 분석한 내용입니다. 

제기된 문제가 옳다는 사실을 증명하기 위하여 기준 일자 이전보다 대교 내 통행 차량의 수가 감소하여야 합니다. 그러나 반포대교를 포함한 인근 대교를 지나가는 차량의 수는 소폭 증가하였습니다. 그러므로 이 근거는 제기된 문제가 옳다는 사실을 증명하는 데 타당하지 않은 근거입니다.

### 4.2. 통행 차량의 속도
다음은 반포대교를 포함한 인근 대교를 지나가는 차량의 속도를 분석한 내용입니다.

제기된 문제가 옳다는 사실을 증명하기 위하여 기준 일자 이전보다 대교 내 통행 차량의 속도가 감소하여야 합니다. 그러나 반포대교, 그리고 동작대교는 오히려 통행 차량의 평균 속도가 소폭 증가하였습니다. 한강대교, 그리고 한남대교는 통행 차량의 속도가 감소하였습니다. 그러나 그 감소분이 크지 않습니다. 그리고 이의 명확한 원인을 찾을 수 없었으나 사회적 거리두기 해제로 인한 영향으로 해석하였습니다. 그러므로 이 근거도 제기된 문제가 옳다는 사실을 증명하는 데 타당하지 않은 근거입니다. 

### 4.3. 종합
사회적 문제, 즉 대통령이 집무실을 이전하였기 때문에 교통 체증이 발생하고 있다는 사실을 옳다고 가정하였습니다. 이 사실이 옳다는 점을 증명하기 위하여 다음을 가정하였습니다. 

- 기준 일자 이전보다 반포대교를 포함한 인근 대교 내 통행 차량의 수가 감소하였다.
- 기준 일자 이전보다 반포대교를 포함한 인근 대교 내 통행 차량의 평균 속도가 감소하였다.

그러나 분석 결과에 의하면 위의 가정은 사회적 문제가 옳다는 점을 증명하는 데 타당하지 않은 근거임을 알 수 있습니다. 그러므로 서론에서 옳은 사실이라고 가정하였던 사회적 문제는 옳지 않은 사실입니다.
