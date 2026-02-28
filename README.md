
<h2 align="center"> Senior Quality Engieer </b> • Automation Architecture & CI/CD Governance •  Mobile, API & Distributed Systems </h2>
  

<p align="center">
  <a target="_blank" href="https://www.linkedin.com/in/mariandadzie/">
    <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
<a target="_blank" href="mailto:mdadzie5@gmail.com">
  <img src="https://img.shields.io/badge/GMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/APPIUM-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/WEBDRIVERIO-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/PYTHON-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/GITHUB_ACTIONS-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/DOCKER-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/SAUCE_LABS-informational?style=for-the-badge">
  <img src="https://img.shields.io/badge/ALLURE-informational?style=for-the-badge">
</p>


---

## Choose your view

<details open>
  <summary><b>Recruiter View </b></summary>

  <br/>

I design and scale quality systems that help teams ship faster with confidence.

With 12+ years across FinTech/Payments, Travel, Enterprise SaaS, Retail, and Healthcare-adjacent platforms. 
I’ve led automation initiatives that move teams from manual validation to CI/CD-integrated release governance.

**What you get working with me**:
- Enterprise-grade automation platforms built from zero
- CI/CD quality gates and PR validation pipelines
- Risk-based coverage informed by production observability
- Release confidence grounded in measurable validation
- Strong cross-functional alignment across Engineering, Product, and DevOps
- Mentorship and elevation of quality standards across teams

Focused on building systems that don’t just pass tests - but hold up in production.

</details>

<details>
  <summary><b>Engineer View </b></summary>

  <br/>

**Focus**: CI-first automation platforms across mobile and API systems, built for scalability, parallel execution, environment isolation, and production-grade validation.

**Core themes**:
- Modular framework architecture (Page/Screen Object patterns)
- Tag-driven execution (smoke/regression/e2e)
- Cloud device execution (Sauce Labs) + Dockerized CI pipelines
- Deterministic runs (seeded data, isolated environments, minimal flakiness)
- Hybrid API + UI validation strategies
- Observability-informed coverage (Sentry, Mixpanel, New Relic)
- Stable, API-driven test data management

**Goal**: Model how quality behaves in production - not just how tests pass locally.
</details>

---

## About Me 

```python
class MarianDadzie:
    def __init__(self, audience: str = "recruiter"):
        self.audience = audience.lower().strip()

        self.name = "Marian Dadzie"
        self.username = "mariand755"
        self.location = "Chicago, IL"
        self.role = "Quality Engineer | Automation Architecture & CI/CD Governance"

        self.focus = [
            "Quality systems that hold up in production",
            "CI-first automation + PR quality gates",
            "Mobile + API + cross-system validation",
            "Release confidence, risk visibility, and measurable stability",
        ]

        self.platforms = ["iOS", "Android", "Web", "Backend APIs", "Distributed Systems"]

        self.industries = [
            "FinTech / Payments",
            "Travel / Booking Platforms",
            "Enterprise SaaS",
            "Retail / E-commerce",
            "Healthcare-adjacent (Regulated)",
            "Big Tech / Infrastructure",
        ]

        self.fun_facts = {
            "born": "Ghana",
            "hobbies": ["Theater", "Gardening", "Baking", "Reading"],
        }

        self.looking_for_roles = [
            "Staff / Principal Quality Engineer",
            "Test Automation Architect",
            "Quality Platform Engineer",
            "Lead QA Engineer",
        ]

    def summary(self):
        if self.audience == "engineer":
            return (
                f"{self.name} designs CI-integrated automation platforms across mobile and API systems, "
                f"environment-aware configs, parallel execution, and quality gates that reduce noise and increase trust."
            )
        return (
            f"{self.name} builds quality systems that help teams ship faster with confidence, "
            f"automation architecture, CI/CD quality gates, and cross-system validation."
        )

    def looking_for(self):
        roles = ", ".join(self.looking_for_roles[:-1]) + f", and {self.looking_for_roles[-1]}"
        return (
            f"Open to {roles} roles where I can strengthen release confidence, "
            f"scale automation thoughtfully, and mentor engineers toward production-ready quality practices."
        )

    def __repr__(self):
        return (
            f"<{self.name} | {self.role} | "
            f"Mobile Platforms: {', '.join(self.platforms)}>"
        )


if __name__ == "__main__":
    me = MarianDadzie(audience="recruiter")

    print(me.summary())       
    print(me.looking_for())   


```



