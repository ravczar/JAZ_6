# JAZ_6
-payara 5.181
-mvn 3.7
1) asadmin start-domain
2) asadmin deploy target/restapp.war
3) http://localhost:8080/restapp
Twoim zadaniem jest zaprojektowanie strony na której użytkownik będzie mógł sprawdzić pogodę w wybranych większych miastach Polski:  Warszawa  Gdańsk  Kraków  Wrocław  Poznań  Łódź  Katowice  Serwis należy zintegrować z zasobami api do przewidywania pogody:  http://openweathermap.org/api  Zapoznaj się z dokumentacją serwisu:  http://openweathermap.org/current  Aby móc korzystać z zasobów powyższego serwisu należy sobie założyć darmowe konto – w nim wygenerować sobie klucz potrzebny do ściągania danych.  Informacje jakie chcemy wyświetlić w naszym serwisie to:  Poziom zachmurzenia  Temperatura w C  Ciśnienie  Prędkość wiatru 
