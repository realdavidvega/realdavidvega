### Hi there 👋

```kotlin
val `David 👨‍💻`: Person =
    person {
        `from 📍` = "Madrid, Spain"
        education = education {
            degree = "Computer Science"
            university = "Technical University of Madrid"
        }
        `occupation 🏢` = occupation {
            role = "Software Engineer"
            at = "Xebia Functional"
            focusedOn = Tech("Backend") {
                "Microservices", "Kotlin",
                "Ktor", "Spring",
                "Arrow", "Coroutines"
            }
        }
        `learning 🌱` = currentlyLearning {
            topics = buildList {
                add("AI")
                add("Kotlin Multiplatform")
            }
        }
        `interests 💞️` = interestedOn {
            topics = arrayOf(
                "Functional Programming",
                "Artificial Intelligence",
                "Fullstack Development",
                "React", "Rust", 
                "JVM", "Scala")
        }
        `contact 📫` = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
        }
    }
```
