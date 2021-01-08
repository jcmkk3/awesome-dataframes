# Awesome Dataframes

An awesome list of dataframe (and dataframe-like) libraries. This list focuses on libraries and tools intended for local (on your personal computer) manipulation of tabular data.

## Libraries

Python
- [pandas](https://github.com/pandas-dev/pandas) - Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more.
- [Modin](https://github.com/modin-project/modin) - Speed up your Pandas workflows by changing a single line of code.
- [Lemuras](https://github.com/AivanF/Lemuras) - A small *pure* Python library to deal with big tables.
- [Ibis](https://github.com/ibis-project/ibis) - A pandas-like deferred expression system, with first-class SQL support.
- [agate](https://github.com/wireservice/agate) - agate is a Python data analysis library that is optimized for humans instead of machines. It is an alternative to numpy and pandas that solves real-world problems with readable code.
- [Prosto](https://github.com/prostodata/prosto) - A Python data processing toolkit to programmatically author and execute complex data processing workflows. Conceptually, it is an alternative to purely set-oriented approaches to data processing like map-reduce, relational algebra, SQL or data-frame-based tools like pandas.
- [siuba](https://github.com/machow/siuba) - Python library for using dplyr like syntax with pandas and SQL.
- [Vaex](https://github.com/vaexio/vaex) - A high performance Python library for lazy Out-of-Core DataFrames (similar to Pandas), to visualize and explore big tabular datasets.
- [dfply](https://github.com/kieferk/dfply) - dplyr-style piping operations for pandas dataframes.
- [kadro](https://github.com/koaning/kadro) - A friendly pandas wrapper with a more composable grammar support.
- [dexplo](https://github.com/dexplo/dexplo) - Data exploration library with a pandas-like API.
- [pands_cub](https://github.com/tdpetrou/pandas_cub) - A detailed project that teaches you how to build your own Python data analysis library, pandas_cub, from scratch.
- [fletcher](https://github.com/xhochy/fletcher) - Pandas ExtensionDType/Array backed by Apache Arrow

R
- [dplyr](https://github.com/tidyverse/dplyr) - A grammar of data manipulation, providing a consistent set of verbs that help you solve the most common data manipulation challenges.
- [data.table](https://github.com/Rdatatable/data.table) - Provides a high-performance version of base R's `data.frame` with syntax and feature enhancements for ease of use, convenience and programming speed.
- [dance](https://github.com/romainfrancois/dance) - Dancing 💃 with the stats, aka `tibble()` dancing 🕺. dance is a sort of reinvention of dplyr classic verbs, with a more modern stack underneath, i.e. it leverages a lot from vctrs and rlang.

JavaScript
- [Arquero](https://github.com/uwdata/arquero) - A JavaScript library for query processing and transformation of array-backed data tables. Following the relational algebra and inspired by the design of dplyr, Arquero provides a fluent API for manipulating column-oriented data frames.
- [dataflow-api](https://github.com/vega/dataflow-api) - JavaScript API for dataflow processing using the vega-dataflow reactive engine. Perform common database operations (sorting, filtering, aggregation, window calculations) over JavaScript objects.
- [datalib](https://github.com/vega/datalib) - A JavaScript data utility library. It provides facilities for data loading, type inference, common statistics, and string templates.
- [Data-Forge](https://github.com/data-forge/data-forge-ts) - The JavaScript data transformation and analysis toolkit inspired by Pandas and LINQ.
- [zebras](https://github.com/nickslevine/zebras) - A data manipulation and analysis library written in JavaScript offering the convenience of pandas or R.
- [dataframe-js](https://github.com/Gmousse/dataframe-js) - A javascript library providing a new data structure for datascientists and developers.

Julia
- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) - Tools for working with tabular data in Julia.
- [DataKnots.jl](https://github.com/rbt-lang/DataKnots.jl) - A Julia library for querying data with an extensible, practical and coherent algebra of query combinators.
- [Volcanito.jl](https://github.com/johnmyleswhite/Volcanito.jl) - Backend agnostic for tabular data operations in Julia.
- [Query.jl](https://github.com/queryverse/Query.jl) - A package for querying julia data sources. It can filter, project, join and group data from any iterable data source, including all the sources supported in IterableTables.jl.

Clojure
- [tech.ml.dataset](https://github.com/techascent/tech.ml.dataset) - A Clojure high performance data processing system.
- [tablecloth](https://github.com/scicloj/tablecloth) - Dataset manipulation library build on the top of tech.ml.dataset.

C++
- [DataFrame](https://github.com/hosseinmoein/DataFrame) - A C++ statistical library that provides an interface similar to Pandas package in Python.

Elm
- [tidy](https://github.com/gicentre/tidy) - Leaning heavily on the principles of the tidyverse, and especially tidy data, this package makes it easy to reshape and tidy tabular data for easier data analysis and visualization.

Java
- [Tablesaw](https://github.com/jtablesaw/tablesaw) - Java dataframe and visualization library.

Kotlin
- [krangl](https://github.com/holgerbrandl/krangl) - A {K}otlin library for data w{rangl}ing.

Ruby
- [rover](https://github.com/ankane/rover) - Simple, powerful data frames for Ruby.
- [daru](https://github.com/SciRuby/daru) - daru (Data Analysis in RUby) is a library for storage, analysis, manipulation and visualization of data in Ruby.

Rust
- [polars](https://github.com/ritchie46/polars) - A blazingly fast DataFrames library implemented in Rust.

Database
- [SQLite](https://sqlite.org/index.html) - A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine
- [DuckDB](https://github.com/cwida/duckdb) - An embeddable SQL OLAP Database Management System.

CLI
- [VisiData](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for discovering and arranging data.

GUI
- [Power Query](https://docs.microsoft.com/en-us/powerquery-m) - A core capability of Power Query is to filter and combine, that is, to mash-up data from one or more of a rich collection of supported data sources.

## Other
- [Arrow](https://github.com/apache/arrow) - A cross-language development platform for in-memory data.
- [Consortium for Python Data APIs](https://data-apis.org/)

## Papers
- [Query Combinators](https://github.com/rbt-lang/rbt-paper)
- [Split Apply Combine](https://www.jstatsoft.org/article/view/v040i01)
- [Towards Scalable Dataframe Systems](https://arxiv.org/pdf/2001.00888.pdf)

## Other Lists
- [Structured Text Tools](https://github.com/dbohdan/structured-text-tools)
- [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)
- [Awesome dataviz](https://github.com/fasouto/awesome-dataviz)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
