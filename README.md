# Combining Flask and Vue
Blog post for [testdriven.io](https://testdriven.io/). If you want to follow along and create the projects yourself, you can find the post [here](https://testdriven.io/blog/combine-flask-vue/).

## Initial Setup
If you don't already have them, install [Git](https://git-scm.com/downloads), [Python](https://www.python.org/downloads/), and [node](https://nodejs.org/en/download/).

In a terminal, Clone the repo to your computer with `git clone https://github.com/based-jace/combining-flask-with-vue.git`. `cd` into the folder.

Next, I recommend creating a Python virtual environment with `python3 -m venv env`. (Optional)

Install the required Python dependencies from the requirements.txt file using `pip install -r requirements.txt`.

## Running the Examples

### Method 1 - Vue in Jinja
In a terminal, `cd` into the "01_vue_in_jinja" folder of your cloned repo. Since you already have everything you need installed, just use `flask run` to start your app in a development server on localhost:5000.

### Methods 2 - Separate Front and Back Ends with Vue
In two terminals, `cd` into the "02_separate_ends" folder of your cloned repo.

In your first terminal, `cd` into the "api" folder. Use `flask run` to start your Flask api in development server on localhost:5000.

In your second terminal, `cd` into the "webapp" folder. Install your node dependencies with `npm install`. Run the development version of the Vue webapp with `npm run serve`. The webapp will be running on localhost:8080.

### Method 2.5 - Separate Front and Back Ends with Nuxt
In two terminals, `cd` into the "02_separate_ends_with_ssr" folder of your cloned repo.

In your first terminal, `cd` into the "api" folder. Use `flask run` to start your Flask api in development server on localhost:5000.

In your second terminal, `cd` into the "webapp" folder. Install your node dependencies with `npm install`. Run the development version of the Nuxt webapp with `npm run dev`. The webapp will be running on localhost:3000.

### Method 3 - Flask Blueprints
In a terminal, `cd` into the "03_flask_blueprints" folder of your cloned repo. Just like Method 1, you already have everything you need installed. Use `flask run` to start your app in a development server on localhost:5000.

### Jace is my hero, but not really ###
