### 3주차 git

### 이미지
![Alt text](/path/to/img.jpg 
"OSS_w3_KAU")![OSS_w3_KAU](https://user-images.githubusercontent.com/127469548/227714922-28779c8e-4190-4ece-9a1d-e51a9be51961.jpg)

### **링크**   
### [LMS](#https://lms.kau.ac.kr/login.php)

### **ProGit 링크**   
### [ProGit](#https://git-scm.com/book/en/v2)   

### 주요 git 명령어 
* add : 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용   
  *  예) git add
* commit
* branch
* merge
* status
* log
  * 예) git log --oneline --decorate --graph --all   
 
 
<hr/>

 ```   
 #!/usr/bin/env bash
 echo "—————\n"
 echo "name :\n"
 
 echo
 
 echo "—————\n"
 echo "student id : \n"
 
 $find /home/kau2/k -name w2_homework.txt 2> /dev/null >> result.txt
 cat result .txt
 
 echo "—————\n"
 echo "line number :"

wc -l /home/kau2/k/w2_homework.txt >> ret2.txt
cat ret2.txt

 echo "—————\n"
 echo "last line :"
 
 tail -1 /home/kau2/k/w2_homework.txt >> ret3.txt
 cat ret3.txt
 
 exit 0
```   
## 마크다운    

### 목록   

#### 번호 있는 목록 : 내림차순 정렬   
1. 첫번째
2. 세번째
3. 두번째

----
#### 번호 없는 목록 : *,-,+   
* 첫번째
* 세번째
* 두번째   

----    
* 빨강
   - 녹색
        + 파랑  

#### 강조   
_single asterisks_   
*single underscores*   
__double asterisks__   
**double underscores**   
~~cancelline~~
