# Instructions: Adding New People Page

To add a new people page, follow these steps:

1. Upload one of your handsome photo as your profile to `assets/img/` folder with filename `{firstname}_{lastname}.jpg`.
2. Create a new markdown (`*.md`) inside `_projects/` with filename `{firstname}_{lastname}.md`.
3. Then fill the **Front Matter** in the markdown file. An example is available at `_projects/template.md`, as well as shown below:

    ```yaml
    ---
    layout: page
    title: Firstname Lastname
    description: PhD Candidate
    img: assets/img/{firstname_lastname}.jpg 
    redirect: 
    importance: 10 
    category: current 
    ---
    ```

    Change key values according to your own cases.
    - `title`: your full name. (*Please captialize the first char.*)
    - `description`: your identity, and please use one of `PhD Candidate`, `Master Student`, `Undergraduate`, `Visiting Scholar`.
    - `img`: the path of profile your add last step.
    - `redirect`: add link of your own personal website if you have one, otherwise leave it empty.
    - `importance`: [`PhD Candidate`=3, `Master Student`=4, `Undergraduate`=5]
    - `category`: either `currents` or `visitor`.

4. If you want to add more details about yourself, please feel free to add anything below the **Front Matter** in the mardown.