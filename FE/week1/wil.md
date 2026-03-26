## GDG 프론트엔드 1주차 WIL

### HTML intro

**html**은 hypertext markup language라는 뜻으로, 1989년 *팀 버너스리*에 의해 구상되었다. 당시 인터넷은 *텍스트 기반* 정보 공유 환경이었고, html로 양식을 통일함으로써 정보 공유의 효율성을 높이고자 했다. 

우리가 요청(request)하면 *서버*에서 응답(response)로 html파일을 보낸다.
(Live Server 익스텐션을 통한 임시 로컬 서버를 이용한다.)

마크업 언어는 텍스트 이외의 정보를 포함한다: 
> 데이터의 구조와 형식을 함께 전달할 수 있는 언어

#### HTML TAG 사용
    <h1>가장 큰 제목
    <h2>두번째로 큰 제목
    <title>페이지의 제목
    <p>단락, 내용
> <tagname>content</tagname>의 형식으로 html tag를 사용할 수 있다. 

#### HyperText 사용
_다른 페이지로 넘어갈 수 있게_ 하고 싶은 텍스트를 content 자리에 집어넣고, 
a 태그(anchor)를 사용한다. 

    <a href="./TITLE.html">content</a>

이를 통해 요소는 여는 태그, 속성, 내용과 닫는 태그로 구성됨을 알 수 있다. 
    <tag attribute>content</tag>

웹 문서는 여러 방향으로 연결되고 비순차적이라는 특징을 가지고 있는데, a태그를 통해 다른 문서로 계속해서 넘어갈 수 있다.