# Profile kit

Everything except the README itself. Drop `README.md` and the `assets/` folder into your `Gauravb741/Gauravb741` repo.

## PART 1: Resume analysis

**Merged from 4 resume versions, duplicates removed.**

| | |
|---|---|
| Identity | Gaurav Sharad Bansod · github.com/Gauravb741 · linkedin.com/in/gauravbansod · gauravbansod680@gmail.com · Portfolio (URL not in the PDF text) |
| Education | VIT Bhopal University · B.Tech CSE · expected 2027 · GPA 7.86 / 10 |
| Experience | MPonline Ltd.: Advanced Software Engineering & Development Intern (Library Management System, Java, MVC) and AI/ML Intern (Smart Customer Retail System), both May–Jul 2026 |
| Projects | NITIGATI, GitOps Kubernetes Deployer, Terraform AWS Infra, CAPE, Online Examination & Proctoring System |
| Achievements | Design patent 434354-001, IEEE Ideathon 1st place, self-published book (Jul 2025) |
| Certificates | Google IT Support, Bits and Bytes of Networking, AWS Cloud Practitioner (Intellipaat), AWS Solutions Architecture (Forage), Machine Learning (NPTEL/IIT), Programming in Java (VITyarthi) |

**Derived identity:** a software developer whose strongest evidence spans the whole delivery path: Django/Next.js apps, GitOps CI/CD, Terraform on AWS. AI appears as features (voice pipeline, churn, sentiment), so it sits inside the story rather than beside it.

**Story arc in the README:** build → engineer → automate → deploy → improve.

**Colour system:** cyan = applications/APIs · blue = cloud · lime = DevOps/automation · purple = AI · orange = security/IAM/milestones · magenta = accent.

## PART 2: README

`README.md`. The previous, plainer version is kept as `README.professional.md` if you want to compare.

**Left out on purpose:** GitHub stats cards and a "Currently building / learning" section. The resume has no information for the second, and stats services are often rate-limited and would show whatever your profile happens to show. If you want stats later, add one subtle top-languages card below the stack table.

**Design trade-off:** project cards are single-column tables, not alternating left/right layouts, because alternating columns get cramped on phones.

## PART 3: Assets

| File | Purpose | Size |
|---|---|---|
| `assets/hero.svg` | Animated boot-sequence hero (plays about 4 s, then holds; only the cursor keeps blinking) | 720×300 |
| `assets/divider.svg` | Section divider with one slow dot | 720×8 |
| `assets/what-i-build.svg` | Layered system map with AI/ML branch | 720×486 |
| `assets/architecture-gitops.svg` | Pipeline with moving marker | 720×270 |
| `assets/architecture-terraform.svg` | Terraform lifecycle → AWS components | 720×312 |
| `assets/architecture-nitigati.svg` | App layers + voice onboarding loop | 720×420 |

All are plain SVG with no scripts, their own dark background (readable in light and dark GitHub themes), `<title>`/`<desc>` for accessibility, and the same facts repeated in text in the README. Diagram contents come only from your resume; nothing shows a component the resume doesn't mention.

**External dependency:** the stack icons load from skillicons.dev. If it's ever down, the text list under each icon row still carries the information.

## PART 4: GitHub bio (143 characters)

```
Full-stack + DevOps dev. Django/Next.js apps, GitOps on Kubernetes, AWS via Terraform, and AI features (Whisper + Gemini). CSE @ VIT Bhopal '27
```

## PART 5: Pinned repositories

| Repository | Capability it shows |
|---|---|
| `gitops-kubernetes-deployer` | CI/CD quality gates, container security scanning, GitOps, Kubernetes |
| `tf-aws-infra` | Infrastructure as code, AWS, least-privilege IAM |
| `NITIGATI` | Full-stack architecture, real-time WebSockets, LLM/speech pipeline |
| `Online-Examination-and-Proctoring-System` | Core Java, concurrency, MVC, event handling |
| `CAPE` | Django + React + MongoDB, role-based portals, analytics |

## PART 6: Repository README improvements

I did not open your repositories, so this is a checklist, not a review. Check each item against the actual repo, and only document what exists.

| Repo | Add first |
|---|---|
| `NITIGATI` | Screenshots of the marketplace and onboarding flow; the architecture diagram from `assets/`; setup steps (Django, Next.js, Redis); required environment variables (Gemini key, etc.); how to run the voice pipeline |
| `gitops-kubernetes-deployer` | Pipeline diagram; screenshot of a passing Actions run and the Argo CD UI; how to bootstrap the cluster and Argo CD; manifest layout |
| `tf-aws-infra` | Diagram; module list; required AWS permissions; how to run plan/validate/apply/destroy; a cost/cleanup warning |
| `Online-Examination-and-Proctoring-System` | Screenshots; how to compile and run; sample credentials if any; package layout |
| `CAPE` | Screenshots of the Admin and Student portals; API endpoint list; setup for Django, React and MongoDB |

Also consider: a short "what this demonstrates" line at the top of each README, and a demo link or short screen recording where one is feasible.

## PART 7: Checklist

- [ ] Create a **public** repo named exactly `Gauravb741`
- [ ] Add `README.md` and the `assets/` folder at the root
- [ ] Replace both `YOUR_PORTFOLIO_URL` placeholders
- [ ] Confirm every repo link opens
- [ ] Pin the five repositories above
- [ ] Set the bio from Part 4
- [ ] View the profile on a phone, and in both light and dark theme
- [ ] Check that the Mermaid diagram renders
- [ ] Improve the top two repo READMEs first (NITIGATI and GitOps)
- [ ] Decide whether to keep the "Words Fallen Wrong" and patent entries high on the page

## Quality test summary

- **Recruiter:** name, role, focus and links are visible in the hero; projects start right after the first scroll.
- **Engineer / DevOps:** each project has a diagram plus a deep dive; gates, GitOps and IaC are named specifically.
- **Frontend:** SVGs use inline CSS/SMIL only, scale to 100% width, and are readable at phone widths, though small labels shrink.
- **Honesty:** no metrics, demos or stats; "status → building" and "systemctl" are playful, not claims.
- **Issues fixed:** removed the planned stats block and the "currently building" section (unsupported); kept animation to one hero sequence, a blinking cursor, and slow dash/dot motion on diagrams.
- **Not verified:** I could not render the page on GitHub from here. Preview it once after pushing.
