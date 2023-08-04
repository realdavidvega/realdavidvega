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
            at = "Xebia Functional"
            exes = listOf("Deutsche Bank", "BBVA", "ONETEC", "BABEL")
            currentlyFocusedOn = Tech("Backend") {
                technologies = listOf("LLM", "Microservices", "Hexagonal", "Event Sourcing", "CQRS")
                languages = listOf("Kotlin", "Java")
                libraries = listOf("Xef", "Arrow", "Ktor", "Coroutines", "Spring", "Kafka")
            }
            expertiseOn = Technologies {
                web = listOf("JavaScript", "TypeScript", "Angular", "WebComponents", "Microfrontends", "Node")
                infrastructure = listOf("Openshift", "GCP", "Docker", "Kubernetes")
                cicd = listOf("GitHub Actions", "TeamCity", "Jenkins")
            }
        }
        `learning 🌱` = currentlyLearning {
            topics = buildList {
                add("AI")
                add("Kotlin Multiplatform")
            }
        }
        `interests 💞️` = interestedOn {
            topics = listOf(
                "Artificial Intelligence",
                "Functional Programming",
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
