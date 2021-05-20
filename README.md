# 탐라저장소

탐라저장소는 제주도의 옛이름인 탐라국에서 파생된 이름으로 제주도와 관련된 문화들이 보존하는 아카이브 역할을 하는 웹페이지입니다. 

시간이 지나면서 잊혀지는 제주도 역사과 관련된 설화, 민담, 신화를 장소와 연관지어 제공함으로써 제주 문화에 대한 제주도민 뿐만 아니라 관광객들이 접근성을 높이고 나아가 제주 문화를 기록하여 보존하는 것을 목표로 하고 있습니다.    
 
---
## 설치 및 사용방법



1. [Apache](https://www.apachelounge.com/download/)를 다운로드 합니다. 

2. 압축을 푼 다음 Apache24 폴더를 C: 드라이브 경로로 옮깁니다. 

3.  Apache24/conf 경로에서 httpd.conf 파일을 편집합니다.(Define SRVROOT "C:\Apache24" 로 변경 )

4. 관리자 권한이 있는 명령 프롬프트에서  Apache의 bin 경로로 이동합니다.(cd C:\Apache24\bin) 

5. 명령 프롬프트에 설치 명령문을 입력합니다. (httpd.exe -k install)

6. fork를 하거나 압축파일로 다운 받은 경우 Apache24/htdocs에 덮어씁니다. 

7. ApacheMonitor.exe를 실행한 뒤 <http://localhost/> 또는 <http://localhost:80/>에 접속합니다.   

---
## OPEN API
### 카카오 맵 API

```c
<script type="text/javascript" src="//dapi.kakao.com/v2/maps/sdk.js?appkey=발급받은 APP KEY를 넣으시면 됩니다."></script>
```
발급받은 JavaScript 키를 지도 API의 appkey로 사용하였습니다. 

웹페이지 내 지도 기능이 활성화하여 문화 속 장소를 보여줌으로 이용자가 장소에 대한 흥미를 생기도록 합니다.  


### 신화, 설화, 민담 API

제주 문화 원형에 분류되어 있는 신화, 설화, 민담에 대한 이야기를 PDF 형식으로 볼 수 있습니다. 

제주어와 표준어 두 가지 언어로 쓰인 이야기들로 인해 비교하면서 접하게 되면서 자연스럽게 제주어에 대한 흥미를 이끌어 냅니다. 

---
## OPEN SOURCE
### [PDF.js](https://github.com/mozilla/pdf.js)

반응형 웹 사이트를 구축하기 위한 강력하고 액세스 가능하며 개발자 친화적인 프레임워크 오픈소스입니다.  

프레임워크 자체에서 설정한 스타일을 실행 취소 할 필요를 방지하고 개발자가 효율적인 코드를 작성하고 비용을 절감할 수 있도록 최대한 경량으로 특별히 개발되었습니다.

---
## TO-DO list 

추후 개발이 더 필요한 리스트 목록입니다. 

### UX/ 뷰 디테일 
- [ ] 메인페이지와 상세페이지 템플릿 만들기 
- [ ] 상단 메뉴 적용 
- [ ] 템플릿 이미지 추가하기  
- [ ] 레이아웃 추가하기


### 기능
- [ ] 설화, 민담, 신화 속 장소와 카카오맵 연결하기 
- [ ] PDF 파일 속 내용을 다른 탭으로 넘어가지 않고 볼 수 있게 적용하기 



### 콘텐츠 
- [ ] 설화, 민담, 신화 속 현재 장소 찾기
- [ ] 역사적 인물 추가하기  



---

## License and Copyright
### The MIT License
Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


Copyright 2013 James Jackson-South under the [MIT license](http://opensource.org/licenses/MIT).
