# 다중이용시설 마스크 착용 감시 자율 주행 로봇


> ## 개요
>
> #### 자율주행 로봇의 필요성
> 1. 한 자리에 머물지 않기 때문에 사각지대가 존재하는 CCTV의 단점을 보완할 수 있다.
> 2. 실시간 위치정보와 촬영 데이터를 시각화하여 관리자가 쉽게 확인할 수 있다.
> 3. 인력을 로봇으로 대체함으로써 코로나 확산 가능성을 최소화하고 인력 낭비를 방지할 수 있다.
> 4. 360도 카메라와 인공지능을 활용하여 마스크를 착용하지 않은 사람을 효율적으로 찾아내고 음성경고 및 기록을 할 수 있다.
>
> #### 목적
> 1. 자율주행 로봇이 정해진 루트를 순찰하면서 시설의 실시간 이미지를 촬영한다.
>> - 사전에 제작된 지도 위에 입력된 목표 지점들을 순서대로 반복하여 주행한다.
>> - 순찰 중 등장하는 장애물들을 감지하고 피한다.
> 2. 자율주행 로봇은 다음의 역할들을 수행한다.
>> - 시설 이용객의 마스크 착용 여부를 감지한다.
>> - 마스크 미착용자를 추적 후 경고 멘트를 송출하고 관리자에게 정보를 전달한다.
>> - 마스크 미착용자의 신원을 확보한다.
> 3. 웹을 통해 관리자가 촬영 화면 및 detection 결과를 볼 수 있으며, 필요 시 경고에 대한 알림을 받을 수 있다.
>> - Admin Web에서는 촬영 이미지와 detection결과가 나타난 이미지를 확인할 수 있다.
>> - Web server는 local 환경에서 구축하며 배포하지 않는다.
>> - 관리자는 로그인을 통해 Admin Web을 이용할 수 있다.
> 4. 유사시에 관리자가 로봇을 비상 작동 시킬 수 있다.
>> - Admin Web에서 관리자가 로봇을 강제로 조작할 수 있다.
>> - 필요 시 관리자의 메시지를 로봇에 전달하여 음성을 출력할 수 있다.

> #### 기대효과
> 1. 코로나 예방 수칙 관리 체계의 효율성 증대
> 2. 지속적인 데이터 수집과 로봇 규제 개선에 따른 감시 성능 향상 기대
> 3. 시간의 제약을 받지 않으므로 필요 경비 인력 감소
> 4. 수집된 데이터를 바탕으로 여러 방면으로 활용 가능





