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
            at = "Xebia (formerly 47 Degrees)"
            exes = listOf("Deutsche Bank", "BBVA", "ONETEC", "BABEL")
            currentFocus = Areas("AI", "Microservices") {
                lang = listOf("Kotlin", "Python", "TypeScript")
                ai = listOf("Generative AI", "LLM", "Finetuning", "GPT", "Prompt Engineering", "Agents", "RAG")
                backend = listOf("Spring Stack", "Ktor", "Coroutines", "FastAPI")
                libs = listOf("LangChain", "LangGraph")
            }
            additionalExpertise = Technologies {
                lang = listOf("Java", "Scala", "JavaScript", "Rust")
                fp = listOf("Arrow.kt", "Cats Effect")
                backend = listOf("Kafka", "Hexagonal", "Event Sourcing", "CQRS", "Saga")
                frontend = listOf("Angular", "React", "Lit", "WebComponents", "Microfrontends")
                testing = listOf("Unit Testing", "Integration Testing", "Property-based Testing", "TDD", "BDD")
                infra = listOf("Terraform", "Openshift", "GCP", "AWS", "Docker", "Kubernetes")
                cicd = listOf("GitHub Actions", "TeamCity", "Jenkins")
            }
        }
        `learning 🌱` = currentlyLearning {
            topics = buildList {
                add("LangGraph")
                add("Vercel AI")
                add("Effect TS")
                add("Next.js")
                add("ZIO")
            }
        }
        `interests 💞️` = interestedOn {
            topics = listOf(
    	        "Artificial intelligence",
                "Multiplatform development",
                "Functional programming",
                "Software architecture",
                "Cloud computing"
            )
        }
        `contact 📫` = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
        }
    }
```
