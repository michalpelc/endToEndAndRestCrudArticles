### Prerequisites:

- java 1.8.0_251
- ChromeDriver 87.0.4280.20
- Maven 3.6.3_1
- Selenium Server (Grid) 3.141.59

### How to run:

`mvn clean -U compile <- clean and install dependencies with update`

`mvn clean -U test -DisRemote=false <- run test locally.`

`mvn clean -U test -DisRemote=true <- run test on selenium hub after adding arguments with server and port.`

`eg. mvn test -DisRemote=true -DhubUrl=localhost -DhubPort=4444`

### How to generate test report:
`mvn allure:serve`



