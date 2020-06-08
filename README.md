# java Spring Backend ve RestAPI beginner çalışmasıdır.

**Java Spring Advanced düzeyde başka bir repository yayınlıycam önümüzdeki günlerde detaylı olacak , frontend kısmı ReactJs'de geliştirmek istiyorum **<br/>

**8080 portu dolu hatası alıyorsanız ilk önce , 8080 nin taskID sini buluyoruz**<br/>
**netstat -o -n -a | findstr 0.0:80**<br/>

TaskID sini bulduktan sonra da siliyoruz  TaskID=17128 örnek</br>
**taskkill /PID 17128  /F**<br/>

veya application.properties den çalışma portunu değiştirebilirsiniz.<br/>

bende iki tane mysql olduğu için kullandığım MYSQL80 database mi 3406 porttan çalıştırdım. sizinki büyük ihtimal 3306 olacaktır.<br/> Veya hangi database i kulanıyorsanız ona göre ayar çekersiniz arkadaşlar... <br/>

spring.datasource.url=jdbc:mysql://localhost:3406/


