## 탐라저장소

탐라저장소는 제주도의 옛이름인 탐라국에서 파생된 이름으로 제주도와 관련된 문화들이 보존하는 아카이브 역할을 하는 웹페이지입니다. <br>
시간이 지나면서 잊혀지는 제주도 역사과 관련된 설화, 민담, 신화를 장소와 연관지어 제공함으로써 제주도민 뿐만 아니라 관광객들이 장소를 직접 방문하는 것이 목표로 하고있습니다.   
 
---
### 설치 및 사용방법



1. [Apache](https://www.apachelounge.com/download/)를 다운로드 합니다. 

2. 압축을 푼 다음 Apache24 폴더를 C: 드라이브 경로로 옮깁니다. 

3.  Apache24/conf 경로에서 httpd.conf 파일을 편집합니다.(Define SRVROOT "C:\Apache24" 로 변경 )

4. 관리자 권한이 있는 명령 프롬프트에서  Apache의 bin 경로로 이동합니다.(cd C:\Apache24\bin) 

5. 명령 프롬프트에 설치 명령문을 입력합니다. (httpd.exe -k install)

6. fork를 하거나 압축파일로 다운 받은 경우 Apache24/htdocs에 덮어씁니다. 

7. ApacheMonitor.exe를 실행한 뒤 <http://localhost/> 또는 <http://localhost:80/>에 접속합니다.   



---
### TO-DO list 

추후 개발이 더 필요한 리스트 목록입니다. 
#### UX/ 뷰 디테일 
[ ] 메인 (false)

#### 기능
[ ]  (false)

#### 콘텐츠 
[ ]  (false)


---

### License and Copyright
#### The MIT License
Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Copyright 2013 James Jackson-South under the [MIT license](http://opensource.org/licenses/MIT).
