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
            currentFocus = Areas("AI", "Backend") {
                ai = listOf("Generative AI", "LLM", "Finetuning", "GPT", "Prompt Engineering", "Assistants", "RAG")
                backend = listOf("Kotlin", "Spring WebFlux", "R2DBC", "Ktor", "Coroutines", "Microservices")
                libs = listOf("Xef.ai", "Arrow.kt", "Testcontainers", "Kotest")
            }
            expertiseOn = Technologies {
                backend = listOf("Java", "Spring Boot", "Kafka", "Hexagonal", "Event Sourcing", "CQRS", "Saga")
                frontend = listOf("JavaScript", "TypeScript", "Angular", "WebComponents", "Microfrontends")
                testing = listOf("Unit Testing", "Integration Testing", "Property-based Testing", "TDD", "BDD")
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
