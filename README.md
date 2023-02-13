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
            focusedOn = Tech("Backend" and "DevOps") {
                "Microservices" and "Kotlin"
                "Docker" and "Kubernetes"
                "Ktor" and "Spring"
            }
        }
        learning 🌱 = currentlyLearning {
            "Arrow" and "Coroutines"
        }
        interests 💞️ = interestedOn {
            "Functional Programming"
            "Fullstack Development"
            "Angular" and "React"
            "Java" and "Rust"
        }
        contact 📫 = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
            twitter = "@realdavidvega"
        }
    }
}
```
