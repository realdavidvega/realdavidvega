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
            "Javascript" and "React"
            "Functional Programming"
            "Java" or "Rust"
        }
        contact 📫 = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "david.vega.lichacz@gmail.com"
        }
    }
}
```
