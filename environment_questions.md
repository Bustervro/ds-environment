
# Data Science Environment Assignment

## Question 1
Why is it important to isolate different data science projects?

It is important because different projects might need different versions of Python packages. Keeping projects separate prevents problems and helps each project work correctly.

## Question 2
How does uv manage packages automatically?

uv automatically creates and manages a virtual environment. It uses pyproject.toml to track the packages and uv.lock to save their exact versions. I can use uv run without manually activating the environment.

## Question 3
What is the purpose of pyproject.toml?

The pyproject.toml file stores information about the project and lists the packages needed. If I share my project with another person, they can install the same packages using uv.

## Question 4
What is the difference between uv.lock and pyproject.toml?

The pyproject.toml file lists the packages the project needs. The uv.lock file saves the exact package versions, including dependencies. This helps everyone use the same versions and get consistent results.

## Question 5
Why are speed and efficiency important?

Speed helps developers save time when installing and updating Python packages. uv uses a global cache so it does not have to download the same packages repeatedly. This makes work faster and easier.
