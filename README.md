### Hi there 👋

```kotlin
val David 👨‍💻 =
    person {
        from 📍 = "Madrid, Spain"
        education 🎓 = education {
            degree = "Computer Science"
            university = "Technical University of Madrid"
        }
        occupation 🏢 = occupation {
            role = SoftwareEngineer
            at = XebiaFunctional
            focusedOn = Tech("Backend") {
                "Microservices" and "Kotlin"
                "Ktor" and "Spring"
                "Arrow" and "Coroutines"
            }
        }
        learning 🌱 = currentlyLearning {
            "AI" and "Kotlin Multiplatform"
        }
        interests 💞️ = interestedOn {
            "Functional Programming"
            "Artificial Intelligence"
            "Fullstack Development"
            "React" and "Rust"
            "JVM" and "Scala"
        }
        contact 📫 = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
        }
    }
}
```
