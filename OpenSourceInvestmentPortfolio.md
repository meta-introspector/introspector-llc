# Open Source Investment Portfolio: Rewarding High-Quality Open Source Companies

## Ideas of the Day

If we are to invest capital in companies through an open source-focused portfolio, those companies must meet rigorous criteria to ensure our investments promote sustainable, ethical, and high-quality open source software (OSS). By allocating funds to such companies, we provide them with resources—financial backing, visibility, and growth opportunities—treating this as an activation of positive memes in the tech ecosystem. 

We should hold these companies to strict investment standards, imagining we're staking our portfolio's success on their commitment to OSS excellence. This portfolio would selectively invest in companies that not only produce or support OSS but also embody principles that foster long-term value, community health, and innovation.

### Fitness

Here are the criteria for evaluating companies for inclusion in the open source investment portfolio:

#### Rule Abiding

Does the company publish and adhere to clear rules for its OSS projects? Do they maintain community guidelines that promote inclusivity and fairness?

##### Non-Discrimination

Is the company committed to openness for all contributors and users in its OSS initiatives? 

Does it discriminate against people based on any characteristics? Is there a notion of "preferred" users or contributors? Are certain uses of the OSS restricted or favored, potentially limiting innovation?

#### Documentation Quality

Companies with well-documented OSS projects are more likely to attract talent and sustain growth, making them stronger investment targets. Is the documentation built on open standards, reproducible from source, and hosted on free platforms without barriers like logins or privacy-invasive services (e.g., avoiding proprietary hosts like Medium or YouTube for core docs)?

#### Industry Standards

Assess the company's alignment with industry best practices in OSS development, such as code quality benchmarks, interoperability, and ethical AI guidelines where applicable.

#### Governance

Evaluate the company's OSS governance model, including transparent decision-making processes that involve the community.

#### Well-Supported

Is the company's OSS ecosystem established and robust? Does it have a sufficient developer base? Is the community vibrant, with active contributions? Are pull requests promptly reviewed?

##### Update Frequency

Factor in the company's track record on update frequency for its OSS projects and rapid response to security vulnerabilities, as these indicate reliability and long-term viability.

### Engagement

Does the company actively engage with OSS contributors? 

Do leaders listen, understand, and incorporate feedback? Is contributor retention high, or is there high turnover? Are pull requests reviewed in detail, line by line? Are patches and bug reports addressed promptly and fairly, treating contributors as valued partners?

### Tracking and Data Collection

Does the company's OSS track user behavior by default (e.g., opt-in vs. opt-out telemetry)? Does it prioritize user privacy? Can the software run without mandatory cloud dependencies, allowing self-hosting?

For additional evaluation questions, reference resources like the F-Droid Inclusion Policy (https://f-droid.org/en/docs/Inclusion_Policy/).

### Free/Libre Open Source Software Commitment

Is the company deeply committed to freedom, sharing, and openness in its core business model?

Are end-user license agreements required, or is usage truly unrestricted? Has the OSS license been vetted and approved by bodies like the Open Source Initiative?

The portfolio prioritizes companies with unwavering OSS dedication, though pragmatic exceptions may apply. Is this commitment long-term, backed by sustainable structures like foundations? Can it be revoked unilaterally?

#### Exceptions

##### NVIDIA-Like Proprietary Dependencies
In cases like NVIDIA's CUDA for ML, investments might include companies reliant on such tech if no OSS alternatives exist, but with a push toward open transitions.

##### Cloud Services When Essential
Companies using AWS, GCP, or Azure could qualify if they abstract dependencies via OSS tools like Kubernetes, promoting cloud-agnostic portability.

### Quality Systems

Every company in the portfolio should have a robust "fitness" or quality function for its OSS projects, measuring health and sustainability. If absent, the company must demonstrate a clear plan to implement one.

#### Pre-Commit Hooks
Are mechanisms in place to prevent bad code from entering repositories?

#### Testing Procedures
Is testing well-defined and accessible, ensuring code reliability?

#### Action on Failing Tests
Are failing tests and checks actively addressed? Are error trends decreasing, signaling improving quality?

### Secure

Companies must implement security best practices in their OSS, from code audits to vulnerability disclosure policies.

### Reproducibility

Portfolio companies should ensure their OSS is reproducible, built on secure, stable foundations—or interchangeable ones (e.g., Kubernetes for clouds)—with no viable alternatives excused only temporarily.

#### Supply Chain Attacks

##### License Switching
View license changes from OSS to restrictive terms (e.g., LiteLLM, OpenFaaS, HashiCorp's Terraform) as red flags, akin to supply chain risks that erode trust.

##### Non-Free Core
Companies promising future openness while starting proprietary may capture markets unfairly, disqualifying them unless they fully commit to OSS.

### Automation

To bolster OSS infrastructure, companies should automate processes to minimize human error. Manual commands or UIs introduce risks; thus, prioritize firms using tools like Terraform for infrastructure as code. Even better if they offer tools to automate API calls or reverse-engineer manual setups.

If full automation isn't feasible, require detailed, version-tracked documentation as a baseline.

By curating this open source investment portfolio around these criteria, we reward companies that exemplify high-quality OSS, driving positive change in the ecosystem and yielding ethical, sustainable returns.

### Source
Originally published: https://github.com/meta-introspector/time/blob/3f6c621561e891c7052fba473cdc22e26bc8691c/2024/07/27/notes.org#L5
