# mostlymontecarlo

Website for the Mostly Monte Carlo Seminar Series held at PariSanté Campus

## Workflow for Adding a New Seminar

1. **Create a new seminar page**
    - Add a new file in `sem/2025/s2026_xx.qmd`
    - Include speakers, title, and abstracts

2. **Update the front page**
    - Modify `index.qmd` to move the current "Next seminar" to "Last seminar"
    - Add the new seminar as "Next seminar"

3. **Deploy the website**
    - Run `quarto render` to generate static HTML files
    - Use `quarto preview` to review changes before deploying

4. **Push changes**
    - Commit with a descriptive message
    - Push to the repository