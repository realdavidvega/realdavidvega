### Hi there 👋

```kotlin
val `David 👨‍💻`: Person =
    person {
        `from 📍` = "Madrid, Spain"
        `education 🎓` = education {
            degree = "Computer Science"
            university = "Technical University of Madrid"
        }
        `occupation 🏢` = occupation {
            role = "Software Engineer"
            at = "Xebia Functional (previously 47 Degrees)"
            exes = listOf("Deutsche Bank", "BBVA", "ONETEC", "BABEL")
            currentFocus = Areas("Backend", "AI") {
                tech = listOf("Generative AI", "Microservices")
                lang = listOf("Kotlin")
                libs = listOf("Xef", "Arrow", "Ktor", "Coroutines")
            }
            expertiseOn = Technologies {
                backend = listOf("Java", "Spring Boot", "Kafka", "Hexagonal", "Event Sourcing", "CQRS", "Saga")
                frontend = listOf("JavaScript", "TypeScript", "Angular", "WebComponents", "Microfrontends")
                infra = listOf("Openshift", "GCP", "AWS", "Docker", "Kubernetes")
                cicd = listOf("GitHub Actions", "TeamCity", "Jenkins")
            }
        }
        `learning 🌱` = currentlyLearning {
            topics = buildList {
                add("AI")
                add("Rust")
                add("Kotlin Multiplatform")
            }
        }
        `interests 💞️` = interestedOn {
            topics = listOf(
                "Architecture",
                "AI",
                "FP",
                "Fullstack",
                "React",
                "JVM",
                "Scala"
            )
        }
        `contact 📫` = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
        }
    }
```
