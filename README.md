# Dream Team Recruitment – Phase II

Phase II evaluates a candidate’s ability to work in a **real developer environment** and build a **production-oriented full-stack web application** using modern tools, workflows, and best practices.

Candidates are expected to be **self-driven**, comfortable reading documentation, and capable of learning independently.

> Refer the official recruitment [documentation](https://amritadreamteam.gitbook.io/joindreamteam) for all queries.

---

## What You Are Expected to Learn

By completing Phase II, candidates are expected to gain hands-on experience with:

1. Git & GitHub (professional workflow)
2. Linux command line usage (Linux/macOS only)
3. JavaScript fundamentals
4. React.js
5. Next.js
6. JSX (no standalone HTML files)
7. Tailwind CSS
8. Flask (backend development)
9. API usage (internal & third-party)

---

## Task List

| Task No. | Task Name                             |
| -------- | ------------------------------------- |
| 0        | Linux                                 |
| 1        | CLI & Git                             |
| 2        | Automate the Boring Stuff with Python |
| 3        | Frontend Development                  |
| 4        | Backend Development                   |

---

## Submission Guidelines

1. **Set up a private GitHub repository named `dreamteam-phase-II`.**

2. **Create directories named `task-#`**  
   (`#` corresponds to the task number).  
   All files, screenshots, code, and deliverables **must be placed inside the correct task directory**.

3. **Each task directory must contain a `writeup.md`** explaining:
   - what you built
   - key decisions
   - challenges faced
   - what you learned

4. **Make a README.md file in the root of your repository and answer the following questions in it**
   - A brief introduction about yourself
   - Why should we choose you
   - How do you plan on contributing back to the club

---

> Clear organization and documentation are mandatory. Failure to adhere to the above guidelines indicates lack of attention to detail and may lead to disqualification.

---

## TASK 0: Linux

### Why Linux?

- **Open & Transparent** – strong community support
- **Developer-first** – powerful CLI and tooling
- **Foundation skill** – essential for real-world software engineering

Candidates **must work on Linux or macOS only**.  
Windows is **not allowed**.

- Recommended OS: **Ubuntu 24.04 LTS**
- macOS users must install **Homebrew** as their package manager

📌 After setup, upload a **screenshot of your desktop (Linux/macOS)** in the task directory as proof.

---

## TASK 1: CLI & Git

### **Objectives**

- Complete **Bandit** up to **Level 20**
- Complete all challenges on **Git Exercises**
- Practice branching, merging, and rebasing using **Learn Git Branching**

### Deliverables

- Screenshots of:
  - Each level of bandit you completed, clearly showing your terminal and username within
  - Git exercises completion page
- A **blog (on medium) or write-up(in task README.md)** explaining:
  - what you learned
  - common mistakes
  - useful commands

Resources:

- https://overthewire.org/wargames/bandit/
- https://gitexercises.fracz.com/
- https://learngitbranching.js.org/
- `man git`

---

## TASK 2: Automate the Boring Stuff with Python

This task evaluates your ability to write **practical Python scripts**, work with files, automation, and apply programming concepts to solve real-world problems.

### Objectives

- Complete Chapters **12, 13, 18, and 19** from _Automate the Boring Stuff with Python_
- Gain hands-on experience with:
  - File handling
  - Regular expressions
  - Web automation / scraping basics
  - Spreadsheet and PDF processing
- Use Git professionally while developing scripts

### Deliverables

Inside the `task-2/` directory, submit the following:

1. **Python scripts (`.py`) for each chapter**
   - Each script must solve at least **one meaningful problem** from the chapter
   - Scripts must be executable and clearly structured

2. **`writeup.md`** explaining:
   - What each script does
   - Why you implemented it the way you did
   - Challenges faced and how you overcame them
   - Key learnings from each chapter

> Submissions containing copied code without explanation or experimentation will be rejected.

### Resources

- Automate the Boring Stuff with Python (Free Online Book)  
  https://automatetheboringstuff.com/

- Python Documentation  
  https://docs.python.org/3/

---

## TASK 3: Frontend Development

Choose **ONE** of the following problem statements:

### Problem Statements

1. **Habit Formation & Streak Analytics App**
   - Mark daily habit completions, track streaks (current, longest), generate analytics (trends, success rate, missed days)
2. **Book Summary & Similar Reads Finder**
   - Generate book summaries, find new books, bookmark them etc.
3. **Ingredient to Recipe Suggester**
   - Generate possible recipes with just a list of ingredients available at hand, etc.

> Above descriptions are just hints at what you can apply in the projects. Problem statements carry no relative weightage, instead evaluation is strictly dependent on your creativity and how in-depth you are willing to go and implement.

---

### Frontend Technical Requirements (Mandatory)

- Must be built using **Next.js with React**
- UI must be written using **JSX**
  - Standalone `.html` files are **not allowed**
- Styling must be done using:
  - **Tailwind CSS** (preferred)
  - or CSS Modules
- Components must be reusable and modular
- Handle loading and error states
- Prepare the UI for backend API integration
- Maintain a list of hardcoded values to be replaced later
- Submissions that only focus on UI without meaningful state, logic, or API readiness will be rejected

---

### React Concepts Expected

Candidates are expected to demonstrate correct usage of:

- `useState` – component state management
- `useEffect` – handling side effects (API calls, updates)
- Conditional rendering
- Component composition
- Props and data flow
- Clean folder and component structure

Static or purely hardcoded UIs will be considered **incomplete**.

## References
- [React Docs](https://react.dev/) – used for hooks and state patterns
- [Next.js Docs](https://nextjs.org/docs) – routing and data fetching
- [Tailwind Docs](https://tailwindcss.com/) – layout and responsive utilities

---

## TASK 4: Backend Development

Build the backend for the **same problem statement** chosen in Task 2.

### Backend Technical Requirements

- Use **Flask**
- Implement RESTful APIs
- Implement **JWT-based authentication** (mandatory)
- Validate inputs properly
- Use meaningful HTTP status codes
- Follow clean project structure
- Candidates are free to choose appropriate third-party APIs, provided they are documented and legally usable.

---

### Authentication Requirement (Mandatory)

All applications **must implement authentication using JWT**, including:

- User registration
- User login
- Protected routes
- Token-based access to APIs

This applies to **all three problem statements**.

---

### API Usage Expectations

- **Habit Analytics App**
  - Internal APIs for habits, streaks, and analytics
- **Book Summary App**
  - Integration with third-party book / summary APIs
- **Recipe Suggester App**
  - Integration with third-party ingredient / recipe APIs

Candidates must:

- Read API documentation
- Handle API failures gracefully
- Avoid hardcoding API responses

## References
- [Flask Docs](https://flask.palletsprojects.com/en/stable/) – application structure & request handling

---

## Interview Evaluation Focus

Candidates will be evaluated on:

- Git commands & GitHub workflow
- Linux commands (basic navigation, file operations, permissions, processes)
- JavaScript fundamentals
- React & Next.js understanding
- API integration and design
- Backend structure and logic
- Code readability and documentation

> **Tip:** Google is your best friend.  
> We expect candidates to research, read docs, debug independently — and only then ask for help (or GPT 😉).

---

Good luck, and build responsibly.

> **_Bonus Tip_** : These tasks are very much doable with consistent effort, so submit your repository even if you don't feel confident, leave the judging to us :)
