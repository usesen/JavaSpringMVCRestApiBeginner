# testJava
java deneme
Java Maven hibernate ve MVC spring test working
Entities oluşturuldu
Proje test çalışmaları devam ediyor şu anda çalışır halde ( Refactor yapılacak tabi ki önümüzdeki günlerde ) 

8080 portu dolu hatası alıyorsanız ilk önce , 8080 nin taskID sini buluyoruz
netstat -o -n -a | findstr 0.0:80

TaskID sini bulduktan sonra da siliyoruz 17128 TaskCID
taskkill /PID 17128  /F

veya application.properties den çalışma portunu değiştirebilirsiniz.

bende iki tane mysql olduğu için kullandığım MYSQL80 database mi 3406 porttan çalıştırdım. sizinki büyük ihtimal 3306 olacaktır. Veya hangi database i kulanıyorsanız ona göre ayar çekersiniz arkadaşlar... 

spring.datasource.url=jdbc:mysql://localhost:3406/


