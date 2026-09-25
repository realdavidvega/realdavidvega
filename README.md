### Hi there 👋

I build AI systems that work in production, not in demos.

```kotlin
val `David 👨‍💻`: Person =
    person {
        `from 📍` = "Madrid, Spain"
        `languages 🗣️` = listOf("Spanish", "Polish", "English")
        `education 🎓` = education {
            degree = "BSc Computer Engineering"
            university = "Technical University of Madrid (UPM)"
            also = "ThePowerMBA, Future Leaders"
        }
        `occupation 🏢` = occupation {
            role = "Staff Software Engineer"
            at = "Xebia (formerly 47 Degrees)"
            exes = listOf("Deutsche Bank", "BBVA", "ONETEC", "BABEL")
            currentFocus = Areas("Agentic AI", "LLM Platforms", "Backend") {
                domain = "Agentic AI for pharmaceutical and other regulated industries"
                lang = listOf("Python", "Kotlin", "TypeScript")
                ai = listOf("Multi-Agent Systems", "RAG", "Hybrid Search", "LLM Evaluation", "LLM-as-Judge", "MCP")
                libs = listOf("LangGraph", "LangChain", "LiteLLM", "Langfuse")
                models = listOf("Claude", "Gemini", "Azure OpenAI", "Bedrock", "vLLM")
                backend = listOf("FastAPI", "Ktor", "Spring Stack", "Coroutines")
                data = listOf("Weaviate", "PostgreSQL", "Redis")
            }
            highlights = listOf(
                "Designed Cortex Query Language: typed DSL, grammar, type system and LSP tooling",
                "Built retrieval agents and the eval harness that proves changes actually help",
                "Rebuilt a documentation pipeline: async workers and processes running concurrently and efficiently"
            )
            additionalExpertise = Technologies {
                lang = listOf("Java", "Scala", "JavaScript", "Rust")
                fp = listOf("Arrow.kt", "Cats Effect")
                backend = listOf("Kafka", "Hexagonal", "Event Sourcing", "CQRS", "Saga")
                languageEngineering = listOf("DSLs", "Xtext", "LSP")
                frontend = listOf("React", "Angular", "Lit", "WebComponents", "Microfrontends")
                testing = listOf("Unit Testing", "Integration Testing", "Property-based Testing", "TDD", "BDD", "Load Testing")
                infra = listOf("GCP", "AWS", "Terraform", "Docker", "Kubernetes", "Openshift")
                observability = listOf("OpenTelemetry", "Grafana", "Prometheus", "Datadog")
                cicd = listOf("GitHub Actions", "Azure DevOps", "TeamCity", "Jenkins")
            }
        }
        `learning 🌱` = currentlyLearning {
            topics = buildList {
                add("Forward Deployed Engineering")
                add("Gemini Enterprise Agent Platform")
                add("GCP Professional ML Engineer")
                add("OpenAI Agents SDK")
                add("AI Governance and Assurance")
            }
        }
        `interests 💞️` = interestedOn {
            topics = listOf(
                "Agent architecture",
                "Evaluation-driven LLM development",
                "Functional programming",
                "Language design",
                "Software architecture",
                "Cloud computing"
            )
        }
        `writing ✍️` = listOf(
            "Spring Data R2DBC and Kotlin Coroutines (Xebia blog)",
            "Xef.ai, open-source AI library for the JVM (contributor)"
        )
        `contact 📫` = contactMe {
            linkedIn = "linkedin.com/in/david-vega-lichacz"
            email = "davidvegalichacz@gmail.com"
        }
    }
```
