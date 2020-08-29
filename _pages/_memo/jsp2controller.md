---
filename: "tag.md"
permalink: memo/jsp2controller/
author_profile: false
sidebar:
  nav: "docs"
---

.ajax


 	//XHR 생성
  	var ajax = new XMLHttpRequest();

	//주소 설정
  	ajax.open("POST",	contextPath+"/mypage/del_post", false);
  
	//데이터 전송
  	ajax.send();
