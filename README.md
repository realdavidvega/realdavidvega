### Hi there 👋

```kotlin
val David 👨‍💻 =
    person {
        from 📍 = "Madrid, Spain",
        education 🎓 = education {
            degree = "Computer Science"
            university = "Technical University of Madrid, UPM"
        }
        occupation 🏢 = occupation {
            role = SoftwareEngineer
            at = DeutscheBankAG
            focusOn = Tech("Backend" and "DevOps") {
                "Microservices" and "Kotlin"
                "Ktor" or "Spring"
                "Docker" and "Kubernetes"
            }
        }
        learning 🌱 = learning {
            "Arrow" and "Coroutines"
        }
        interests 💞️ = alsoInterestedOn {
            "Functional Programming"
            "Java" or "Rust"
            "Javascript" and "React"
        }
        contact 📫 = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "david.vega.lichacz@gmail.com"
        }
    }
}
```
