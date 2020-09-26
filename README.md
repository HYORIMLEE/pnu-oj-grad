# 한준만들기
## 과제 배경
최근 4차 산업혁명의 흐름에 맞추어, 다양한 분야에서 IT 기술을 활용해서 새로운 흐름을 만들어내고 있다. 이에 맞춰 교육부도 코딩 수업을 교육과정에 필수로 지정하고, 많은 직장인들이 컴퓨터 언어를 학습하는 등 프로그램을 만드는 일에 많은 관심을 보이고 있다. 정부에서도 IT 기술을 다양한 분야에 접목하는 것의 중요성을 인식하고 산업의 이해 및 융합을 위해 많은 노력을 기울이고 있다. 이에 따라 개인, 가정 및 그리고 기업에 이르기까지 다양한 곳에서 코딩을 배우고자 하는 노력이 커지고 있지만, 입문자들을 위한 프로그래밍 연습을 지원하는 플랫폼이 제한적이다.         
## 과제 목표
초/중학생 프로그래밍 입문자를 위한 온라인 저지 사이트를 개발한다. 이를 위한 목표는 다음과 같다.
 1) 유저들의 특성상 쉬운 문제를 단계별로 풀 수 있는 시스템을 도입한다.
 2) 흥미를 유발하기 위해 포인트제, 랭킹시스템, 시즌제 등 게임적 요소를 추가한다. 

## 개발 환경 설정
* Python >= 3.8.x

```
$ git clone https://github.com/HYORIMLEE/pnu-oj-grad.git 
$ cd pnu-oj-grad
$ python -m venv venv
$ venv\Scripts\activate
$ pip install -r requirements.txt
$ python manage.py migrate
$ python manage.py runserver
```

## 참조 링크

Django : <https://www.djangoproject.com>   
DMOJ : <https://docs.dmoj.ca>
