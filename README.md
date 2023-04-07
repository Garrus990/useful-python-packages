In this repository we collate a list of useful python packages divided into groups. The list is subject to grow and grow :)


### Business Intelligence
- [dash](https://dash.plotly.com/) - Plotly-based package to build dashboards.
- [streamlit](https://streamlit.io/) - As above, but possibly even more feature-rich and easier.

### Command Line Interface
- [Click](https://click.palletsprojects.com/en/8.1.x/) - Probably the best package to design a CLI interface. Feature-rich.
- [typer](https://typer.tiangolo.com/) - A follow-up to `Click`. It uses that package internally and adds features on top of it.
- [colorama](https://github.com/tartley/colorama) - Provide some colors in your terminal.
- [rich](https://github.com/Textualize/rich) - Almost everything you can imagine regarding beautification of your text in terminal. And not only text since emojis are supported.
- [argparse](https://docs.python.org/3/library/argparse.html) - Pretty limited in comparison with `Click`, but does the work done.
- [Python Fire](https://github.com/google/python-fire) - Automatically generate Command Line Interface for your app.

### Databases
- [SQLModel](https://sqlmodel.tiangolo.com/) - Based on `SQLAlchemy` and `Pydantic` to simplify database integrations.
- [dataset](https://dataset.readthedocs.io/en/latest/) - Treat databases as JSON files with this package that provides a level of abstraction over `SQLAlchemy`.

### Date and time handling
- [Pendulum](https://pendulum.eustace.io/) - Drop-in replacement for `datetime`.
- [Arrow](https://github.com/arrow-py/arrow) - An alternative to `Pendulum`. Does basically the same things, but with different syntax.

### Deep learning
- [Jarvis](https://github.com/microsoft/JARVIS) - Chaining multiple deep AI models to get the things done. Based on Hugging Face transformers.
- [LangChain](https://github.com/hwchase17/langchain) - An assistant in creation of large-language-models-based applications.
- [Evidently](https://github.com/evidentlyai/evidently) - Validate your models in production.

### Linters / formatters / code quality
- [ruff](https://github.com/charliermarsh/ruff) - Blazingly fast (written in Rust) linter for Python code. Offers what other linters offer, but faster.
- [isort](https://github.com/PyCQA/isort) - Sorting of the imports, so that you do not have to remember about it.
- [pydantic](https://docs.pydantic.dev/) - Data validation. Define data and see if what is being received is what you expect.

### Logging
- [loguru](https://github.com/Delgan/loguru) - Stupidly easy logging. Integrated with the standard `logger` library.
- [rich](https://github.com/Textualize/rich) - Apart from being a command line tool, it also supports logging.
- [whylogs](https://github.com/whylabs/whylogs) - Control over data in your pipelines and see if there is a drift.
- [stackprinter](https://github.com/cknd/stackprinter) - Upgrade the way Python's error stacks are printed. Just make them more informative.

### NLP
- [Texthero](https://texthero.org/) - Text preprocessing, representation and visualization from zero to hero.

### Operating system management
- [pathlib](https://docs.python.org/3/library/pathlib.html) - Replacement for the native `os` package to navigate the folders in a system-agnostic manner. Basically, never again use `os`.

### Packaging / dependency management
- [Poetry](https://python-poetry.org/) - A jack of all traits for packaging and dependency management. It enables seamless versioning across all team members.

### Performance / parallelization
- [joblib](https://joblib.readthedocs.io/en/latest/) - Embarassingly easy parallelization.
- [Ray](https://docs.ray.io/en/latest/ray-overview/index.html) - Scaling of AI and Python application.
- [memray](https://github.com/bloomberg/memray) - Memory profiler for Python code executions.

### Visualizations / plotting
- [matplotlib](https://matplotlib.org/) - The backbone of many visualization packages in Python. Low-level.
- [seaborn](https://seaborn.pydata.org/) - Built on top of `matplotlib`, but natively supports pandas data frames.
- [plotnine](https://github.com/has2k1/plotnine) - Implementation of Grammar of Graphics principle for Python. Syntax closely resembles R's `ggplot`.
- [plotly](https://plotly.com/python/) - Python implementation of one of the most popular plotting libraries. Provides rich interactivity.
- [bokeh](https://bokeh.org/) - Similar to `plotly`, also with emphasis on interactivity.
- [Folium](https://python-visualization.github.io/folium/) - Although other packages support maps, this package specializes in the topic using OpenStreetMap.

### Web-related
- [Beautiful soup](https://beautiful-soup-4.readthedocs.io/en/latest/) - Navigating, searching, and modifying a parse tree of HTML documents. Elegant and powerful.
- [FastAPI](https://fastapi.tiangolo.com/) - Building APIs in Python in minutes, not hours.
