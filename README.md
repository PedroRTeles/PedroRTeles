```kotlin
data class Info(
    val name = "Pedro Teles",
    val age = 22,
    val nationality = "Brazillian",
    val languages = listOf("Portuguese", "English"),
    val college = "InfoSec - FATEC São Caetano do Sul",
    val occupation = "Software Engineer",
    val hobbies = listOf("Programming", "Reading", "Writing", "Travel"),
    val skills = Programming(),
    val socialInfo = Social()
)

data class Programming(
    val languages = listOf("Kotlin", "Java"),
    val platforms = listOf("Android", "Backend"),
    val frameworks = listOf("Spring Boot"),
    val databases = listOf("MySQL", "SQL Server"),
    val learning = listOf("Python", "Kafka", "Machine Learning Concepts"),
    val projects = listOf("Helppet")
)

data class Social(
    val website = "https://pedroteles.dev",
    val linkedin = "https://br.linkedin.com/in/pedro-teles-developer",
    val medium = "https://medium.com/@pedroateles",
    val github = "https://github.com/PedroRTeles"
)
```
