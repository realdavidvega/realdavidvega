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
            role = "Senior Software Engineer"
            at = "Xebia (previously 47 Degrees)"
            exes = listOf("Deutsche Bank", "BBVA", "ONETEC", "BABEL")
            currentFocus = Areas("AI", "Microservices") {
                lang = setOf("Kotlin", "TypeScript", "Java, "Scala")
                ai = listOf("Generative AI", "LLM", "Finetuning", "GPT", "Prompt Engineering", "Assistants", "RAG")
                backend = listOf("Spring Boot", "R2DBC", "Ktor", "Coroutines", "http4s", "node")
                libs = listOf("Xef.ai", "Langchain4j", "Arrow.kt", "Testcontainers", "Kotest", "Cats Effect", "Effect-TS")
            }
            expertiseOn = Technologies {
                backend = listOf("Kafka", "Hexagonal", "Event Sourcing", "CQRS", "Saga")
                frontend = listOf("TypeScript", "Angular", "WebComponents", "Microfrontends")
                testing = listOf("Unit Testing", "Integration Testing", "Property-based Testing", "TDD", "BDD")
                infra = listOf("Openshift", "GCP", "AWS", "Docker", "Kubernetes")
                cicd = listOf("GitHub Actions", "TeamCity", "Jenkins")
            }
        }
        `learning 🌱` = currentlyLearning {
            topics = buildList {
                add("AI")
                add("Next.js")
            }
        }
        `interests 💞️` = interestedOn {
            topics = listOf(
                "Architecture",
                "AI",
                "FP",
                "Scala",
                "Fullstack",
                "React",
                "JVM"
            )
        }
        `contact 📫` = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
        }
    }
```
