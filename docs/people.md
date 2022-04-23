# Instructions: Adding New People Page

To add a new people page, follow these steps:

1. Upload one of your handsome photo as your profile to `assets/img/` folder with filename `{firstname}_{lastname}.jpg`.
2. Create a new markdown (`*.md`) inside `_people/` with filename `{firstname}_{lastname}.md`.
3. Then fill the **Front Matter** in the markdown file. An example is available at `_people/template.md`, as well as shown below:

    ```yaml
    ---
    layout: page
    title: Firstname Lastname
    description:
    img: assets/img/{firstname_lastname}.jpg 
    redirect: 
    year: 2022 
    category: # PhD Students, Master's Students, Undergraduates or Visiting Students
    email: 
    github_username: 
    google_scholar: 
    ---
    ```

    Change key values according to your own cases.
    - `title`: your full name. (*Please captialize the first char.*)
    - `description`: (optional)
    - `img`: the path of profile your add last step.
    - `redirect`: add link of your own personal website if you have one, otherwise leave it empty.
    - `year`: year you join the lab.
    - `category`: your identity, and please use one of `PhD Students`, `Master's Students`, `Undergraduates`, `Visiting Students`.
    - `email`: (required)
    - `github_username`: (optional) your github username.
    - `google_scholar`: (optional) your google scholar personal site.

4. If you want to add more details about yourself, please feel free to add anything below the **Front Matter** in the mardown.