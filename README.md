# Student Organization Site

## 🚀 Getting Started

1. Open your terminal and navigate to the location where you want to store the project

    ```bash
    cd <PATH TO PROJECT LOCATION>
    ```

2. Clone the repository directly into the current directory

    ```bash
    git clone https://github.com/Viadsss/WebDev-StudentOrgSite.git
    ```

3. Navigate into the project folder

    ```bash
    cd WebDev-StudentOrgSite
    ```

---

## 🤝 Contributing

### 🛠 Contribution Guide

1. Ensure you are on the **`main`** branch

    ```bash
    git checkout main
    git pull origin main
    ```

2. Create a new branch based on the latest **`main`**

    ```bash
    git checkout -b <dev-name>-<task-desc>
    ```

    **Format:** `[dev-name]-[task-desc]`

    | Placeholder   | Description                        |
    | ------------- | ---------------------------------- |
    | `[dev-name]`  | Your nickname                      |
    | `[task-desc]` | Short, hyphenated task description |

    **Example:** `viado-fix-login`

3. Make sure to know what branch you are currently working by entering:

    ```bash
    git branch
    ```

4. Start working on your local copy by adding/editing/removing files

    ```bash
    git add index.html
    git commit -m "fix: align anchor tags"
    ```

    ✅ **Commit Message Format**

    ```bash
    git commit -m "<type>: <short-description>"
    ```

    **Commit Types:**

    - `feat` → A new feature
    - `fix` → A bug fix
    - `refactor` → Code changes that neither fix bugs nor add features
    - `chore` → Maintenance tasks like updating dependencies or configs
    - `docs` → Documentation updates

5. After all changes, to save them to the GitHub repo, follow:

    ```bash
    git add -A
    git commit -m "<type>: <short-description>"
    git push origin <current-branch-name>
    ```

6. Open a Pull Request (PR) on GitHub
    - Navigate to our [GitHub Repository](https://github.com/Viadsss/WebDev-StudentOrgSite) and go to the **Pull Requests** tab
    - Click on the **"New Pull Request**.
    - Select the correct branches:
        - **Base:** `main`
        - **Compare:** `yourname-taskdesc` (your branch)
    - Ensure the PR follows this structure: `base: main <- compare: yourname-taskdesc`.
    - Provide a detailed description following the **Pull Request Description Format** below.
    - **Notify the team** via the Messenger Group Chat.

### 📝 Pull Request Description Format

```
### Changes Includes:
- Add: (List files added + reason)
- Modify: (List files modified + reason)
- Remove: (List files deleted + reason)

### Packages/Libraries Installed:
- [Package Name] - [Reason for adding]

### Questions/Issues:
- (Free format for any concerns)

### Tasks to do (if WIP upon PR):
- (List remaining tasks)
```
