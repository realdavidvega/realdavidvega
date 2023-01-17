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
            at = 47Degrees
            focusOn = Tech("Backend" and "DevOps") {
                "Microservices" and "Kotlin"
                "Docker" and "Kubernetes"
                "Ktor" or "Spring"
            }
        }
        learning 🌱 = currentlyLearning {
            "Arrow" and "Coroutines"
        }
        interests 💞️ = interestedOn {
            "Functional Programming"
            "Fullstack Development"
            "Angular" or "React"
            "Java" or "Rust"
        }
        contact 📫 = contactMe {
            linkedIn = "linkedin.com/in/david-vega-"
            email = "xdavidvega95@gmail.com"
            twitter = "@realdavidvega"
        }
    }
}
```
