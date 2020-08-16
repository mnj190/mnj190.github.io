---
filename: "tag.md"
permalink: memo/tag/
---

	//변수 선언	
	<c:set var = "변수명" value = "변수" />
	
	//변수 삭제
	<c:remove var = "변수명" />
	
	//조건문
	<c:if test="조건"> 출력 내용 </c:test>
	
	<c:chose>
		<c:when test="조건1"> 출력 내용 </c:when>
		<c:when test="조건2"> 출력 내용 </c:when>
		<c:otherwise> 내용 </c:otherwise>
	</c:chose>
	
	//반복문
		//향상된 for문
	<c:forEach var="변수명" items="배열, 리스트, 맵 등" />
	
		//split + 향상된 for문
	<c:forTokens var="변수" items="배열, 리스트, 맵 등"  delims="자를 단위" />
