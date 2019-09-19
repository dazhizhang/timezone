# timezone
<br>
如果时区设置为“UTC”,则SimpleDateFormat忽略“XXX”
<br>
final SimpleDateFormat formatter = new SimpleDateFormat("yyyy-MM-dd'T'HH:mm:ssXXX");<br>
formatter.setTimeZone(TimeZone.getTimeZone("UTC"));<br>
<br>
final String dateString = formatter.format(new Date());<br>
