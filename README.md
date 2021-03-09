# Machine_Learning

# 1. 기계학습 파이썬, 실제 예제분류, 지도학습

교과서 중 수업 범위 : ~98 page, 134~145

# Chapter 1 

1. 구글 드라이브에 MlClass 라는 폴더 만들기 

2. 구글 코랩 실행

실행하자마자 한글 표시 기능 설치

!sudo apt-get install -y fonts-nanum

!sudo fc-cache -fv

!rm ~/.cache/matplotlib -rf

런타임 메뉴에서 런타임 다시 시작 선택


3. 코드로 다음을 실행하여 구글 드라이브 연결

from google.colab import drive

drive.mount('/content/gdrive')

4 구글 드라이브로 이동

cd /content/gdrive/MyDrive/MlClass

5. 깃헙 다운로드

!git clone https://github.com/rickiepark/introduction_to_ml_with_python


cd introduction_to_ml_with_python/

ls

6. 필요 패키지 설치

pip install numpy scipy scikit-learn matplotlib pandas pillow graphviz

7. 문제 없는지 체크

from preamble import *

8. 다른 창에서 구글 드라이브에서 예제 파일을 오른 클릭하여 코랩에서 열기


9. 수업들으면서 하나씩 복사해서 실행하면서 실습 진행

* 중간에 timeout 되면 reconnect 해서 이용.


-----------------------------------------------------------------------------

# Chapter 2 부터

1. 새 노트북 실행

실행하자마자 한글 표시 기능 설치

!sudo apt-get install -y fonts-nanum

!sudo fc-cache -fv

!rm ~/.cache/matplotlib -rf

런타임 메뉴에서 런타임 다시 시작 선택

2. 코드로 다음을 실행하여 구글 드라이브 연결

from google.colab import drive

drive.mount('/content/gdrive')

3 구글 드라이브로 이동

cd /content/gdrive/MyDrive/MlClass/introduction_to_ml_with_python/


ls

4. 필요 패키지 설치

pip install numpy scipy scikit-learn matplotlib pandas pillow graphviz

5. 문제 없는지 체크

from preamble import *

6. 다른 창에서 구글 드라이브에서 예제 파일을 오른 클릭하여 코랩에서 열기

7. 수업들으면서 하나씩 복사해서 실행하면서 실습 진행

------------------------------------
## 2일차는 분류에 대한 선형 모델 부터 시작 (86페이지)
============================================

# 2. 비지도 학습과 데이터 전처리

교과서 중 수업 범위 : 175 ~ 201, 
                     225 ~ 248

# Chapter 3. 

Chapter 2 와 동일



