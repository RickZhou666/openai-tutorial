# openai-tutorial

# OpenAI API Quickstart - Python example app

This is an example pet name generator app used in the OpenAI API [quickstart tutorial](https://beta.openai.com/docs/quickstart). It uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework. Check out the tutorial or follow the instructions below to get set up.

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/).

2. Clone this repository.

3. Navigate into the project directory:

   ```bash
   $ cd openai-quickstart-python
   ```

4. Create a new virtual environment:

   ```bash
   $ python3.10 -m venv .venv
   # $ . venv/bin/activate

   # select python interpreter

   # update pip
   $ pip install --upgrade pip
   ```

5. Install the requirements:

   ```bash
   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file:

   ```bash
   $ cp .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file.

8. Run the app:

   ```bash
   $ flask run
   ```

You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! For the full context behind this example app, check out the [tutorial](https://beta.openai.com/docs/quickstart).

This is a self learning from OpenAI [official site](https://platform.openai.com/docs/)

# 1. Get started

## 1.1 Quickstart

Using OpenAI api for any task:

- Content generation
- Summarization
- Classification, categorization, and sentiment analysis
- Data extraction
- Translation
- Many more!

### 1.1.1 Intro

Input **prompt**, return **completion**

### 1.1.2 Start with an instruction

adding a simple adjective to our prompt changes the resulting completion.

### 1.1.3 Add some examples

### 1.1.4 Adjust your settings

control completions by **temperature**

model predicts which text is most likely to follow the text preceding it.

- Lowering temperature means it will take fewer risks, and completions will be more accurate and deterministic.
- Increasing temperature will result in more diverse completions.
