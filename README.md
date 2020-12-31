# zy
<%@ page language="java" contentType="text/html; charset=utf-8"
    pageEncoding="utf-8"%>
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Insert title here</title>
</head>
<body>
<form action="doServlet?params=update" method="post">
YPNO:<input type="text" name="YPNO" value="${sessionScope.emp2.YPNO }"/><br/>
YPNAME:<input type="text" name="YPNAME" value="${sessionScope.emp2.YPNAME }"/><br/>
SWEET:<input type="text" name="SWEET" value="${sessionScope.emp2.SWEET }"/><br/>
YPSORT:<input type="text" name="YPSORT" value="${sessionScope.emp2.YPSORT }"/><br/>
TEMPERATURE:<input type="text" name="TEMPERATURE" value="${sessionScope.emp2.TEMPERATURE }"/><br/>
<input type="submit" value="提交"/>

</form>
</body>
</html>
