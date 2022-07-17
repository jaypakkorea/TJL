# TJL

> Today Jay Learned





-----

##                                                                                        Time Stamp

-----





### START CAMP

----

> [**Setting_Basic**](https://hphk.notion.site/SSAFY-8-Public-Document-9dc94ea8a050472ca00ffe8ea58586da)

​		개인 노트북에 다운 받기 



> **CODING**



- **While / For** 문 예제

  - 로또 :

    ***1부터 45 사이 숫자 6개를 무작위로 고르고, 이 숫자들이 로또 당첨번호와 같은지 확인하는 알고리즘을***

    ***만들어라.***

    ```python
    numbers = list ( range(1,46) )
    
    import random
    
    winner = [ 10, 14, 16, 18, 29, 35 ]
    
    for chance in range(100000) :
        lucky = random.sample(numbers, 6)
    
        member = 0
    
        for i in range (6) :
            if lucky[i] in winner :
                member += 1
                
        if member == len(winner) :
            print ("정답")
    ```

    ---

    

    ​	***What Jay Learned***

    ​			- 문제 해결을 위한 **Logic** 을 먼저 생각하고, 그 뒤 필요한 Code를 생각하자.

    ***				'어떻게 하면 로또번호 당첨 여부를 확인하는 알고리즘을 짤까?'***

    ***				'먼저 내가 선택한 6개의 숫자 가 당첨 번호에 있나 확인'***

    ***				'그 6개의 member와 winner의 리스트 length가 같은지 확인'***

    

    ​			-  좋은 Code 보단 좋은 **Logic**에 먼저 집중하자.

    

- **Json** 

```python
import requests

url = 'https://api.agify.io/?name=jay'
print(requests.get(url).json())
```



> **Mark Down**

```
#코드 입력법
  1) 인코드 
		` 로 감싸준다
  2) 블록코드
		``` + enter
		
#링크
  [구글](구글주소)
  
  
#이미지
	![이름](주소)
	
#인용
	> 입력
	
#표
	파이프 |
	하이픈 - 
	ctrl + T
	ctrl + enter
	
	
#수평선
	--- 복수로 입력
```









> **GIT**

***How does Github make money?***

Freemium Buisiness like Dropbox , Google Drive



**CLI** & **Gui**

Graphic User Interface

Command Line Interface : 명령 프롬포트 (MS Dos)  

![MS-DOS | Definition, Features, Importance, & Facts | Britannica](TJL.assets/Screenshot-program-screen-MS-DOS.jpg)]



## 절대경로 vs 상대경로 ##

절대경로 : 루트 디렉토리 ~ 목적 파일 모든 경로가 전부 포함 ex) c:/users/ssafy

상대경로 : 현재 작업중인 디렉토리 기준으로 계산한  ex) /a.txt 

​						./	나					

​						../  상위 폴더 

​						기준점 : c:/users/ssafy/sky/a.txt

​						비교     : c:/users/ssafy/jay/k.txt   

​						표시     : ../jay/k.txt



### GIT bash ###



touch a.txt : 파일 만들기

cd .. : 상위 폴더로 이동 (change diretory)

mkdir 'folder test'

start .

pwd

ls

ls -a : all

ls -l : 더 자세한 정보

mv p.txt x.txt (같은 폴더에서 move 를 하면 파일 명을 바꿈)

mv x.txt ../'test folder'

rm x.txt

<VS Code에서 Git bash>

![캡처](TJL.assets/캡처.PNG)

*** git init***

Working Directory (untracked file)

*** git add***

Staging Area

*** git commit*** -m"남기고 싶은 메시지"  ex) "first commit"

Repository



![git init , name, email](TJL.assets/git init , name, email.PNG)



git init (디렉토리를 수정하겠다)

git config --global user.name (수정자를 입력)

git config --global user.email

git status  

git add ny_project.txt 

git rm --cached ny_project.txt

git commit -m "1st commit"

git add ny_project.txt (수정)

git log (추적)

git commit -m "2nd commit"

git log --oneline



> ## GITHub



local pc 

1. clone (첫날) 2. pull (이후)

git remote add origin = 길을 만들어 주는 작업

git -v  = 길이 잘 만들어졌는지 확인

git push -u origin master = 입력



Git hub에 Push 하기

git remote -v (길 확인)

git remote add origin github 주소

git push -u origin master



Git hub 에서 Clone 하기

git clone [저장 주소] [로컬에 복제할 위치] 





### 1_week

-----



### 2_week

-----



### 3_week

-----















 