# Exploring Code Evolution

In this exercise, we will explore code evolution in real systems.

We will use the [GitEvo](https://github.com/andrehora/gitevo) tool.
This tool analyzes code evolution in Git repositories for Python, JavaScript, TypeScript, and Java languages, and generates `HTML` reports like [this one](https://andrehora.github.io/gitevo-examples/python/pandas.html).

More report examples can be found at https://github.com/andrehora/gitevo-examples.

# Step 1: Select a repository to analyze

Select a relevant repository in your preferred language (Python, JavaScript, TypeScript, or Java).
You can find interesting projects at the links below:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

# Step 2: Install and run the GitEvo tool

> [!NOTE]
> Before installing the tool, it is recommended to create and activate a [Python virtual environment](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

Install the [GitEvo](https://github.com/andrehora/gitevo) tool with the command:

```
$ pip install gitevo
```

Run the tool on the selected repository using the command below (adjust according to the repository language).
Replace `<git_url>` with the URL of the repository to be analyzed:

```shell
# Python
$ gitevo -r python <git_url>

# JavaScript
$ gitevo -r javascript <git_url>

# TypeScript
$ gitevo -r typescript <git_url>

# Java
$ gitevo -r java <git_url>
```

For example, to analyze the Flask project written in Python:

```
$ gitevo -r python https://github.com/pallets/flask
```

> [!NOTE]
> This step may take a few minutes as the project will be cloned and analyzed locally.

# Step 3: Explore the code evolution report

After running the [GitEvo](https://github.com/andrehora/gitevo) tool, an `HTML` report containing various charts about code evolution is generated.

Open the `HTML` report and carefully observe the charts.

# Step 4: Explain a code evolution chart

Select one of the evolution charts and explain it in your own words.
For example, you can:

- Detail the evolution over time
- Detail whether the curves are in accordance with best practices
- Explain major changes in the curves
- Explore the repository documentation in search of explanations for major changes
- etc.

Be creative!

# Exercise Instructions

1. Create a `fork` of this repository (more information about forks [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)).
2. Add the `HTML` report to your fork.
3. On Moodle, submit only the URL of your `fork`.

Answer the questions below directly in this `README.md` file of your fork:

1. Selected repository: <SELECTED_REPOSITORY_URL_HERE>
2. Selected chart: <SELECTED_CHART_IMAGE_HERE>
3. Explanation: <EXPLANATION_HERE>


