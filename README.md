doctor ai는 의료 이미지를 이용하여 질병은 판단합니다.
==================================================

제가 제작한 모델은 피부암 양성, 악성 진단 모델입니다. 

* 이미지 데이터 
    * 총 6265장 
    * Train 5000장 양성 2500장 악성 2500장   
    * Test 1265장  양성 663장 악성 602장 
    * 출처 ISIC Archive 

* 프레임워크: Keras
* 신경망: RESNET50 + 전이학습 
