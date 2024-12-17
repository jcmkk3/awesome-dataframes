# Awesome Dataframes

An awesome list of dataframe (and dataframe-like) libraries. This list focuses on libraries and tools intended for local (on your personal computer) manipulation of tabular data.

## Libraries

Python
- [pandas](https://github.com/pandas-dev/pandas) - Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more.
- [Polars](https://github.com/pola-rs/polars) - Fast multi-threaded DataFrame library in Rust and Python.
- [Modin](https://github.com/modin-project/modin) - Speed up your Pandas workflows by changing a single line of code.
- [Ibis](https://github.com/ibis-project/ibis) - A pandas-like deferred expression system, with first-class SQL support.
- [Narwhals](https://github.com/narwhals-dev/narwhals) - Lightweight and extensible compatibility layer between dataframe libraries!
- [agate](https://github.com/wireservice/agate) - agate is a Python data analysis library that is optimized for humans instead of machines. It is an alternative to numpy and pandas that solves real-world problems with readable code.
- [Lemuras](https://github.com/AivanF/Lemuras) - A small *pure* Python library to deal with big tables.
- [datatable](https://github.com/h2oai/datatable) - A Python package for manipulating 2-dimensional tabular data structures.
- [Prosto](https://github.com/prostodata/prosto) - A Python data processing toolkit to programmatically author and execute complex data processing workflows. Conceptually, it is an alternative to purely set-oriented approaches to data processing like map-reduce, relational algebra, SQL or data-frame-based tools like pandas.
- [siuba](https://github.com/machow/siuba) - Python library for using dplyr like syntax with pandas and SQL.
- [Vaex](https://github.com/vaexio/vaex) - A high performance Python library for lazy Out-of-Core DataFrames (similar to Pandas), to visualize and explore big tabular datasets.
- [dfply](https://github.com/kieferk/dfply) - dplyr-style piping operations for pandas dataframes.
- [kadro](https://github.com/koaning/kadro) - A friendly pandas wrapper with a more composable grammar support.
- [dexplo](https://github.com/dexplo/dexplo) - Data exploration library with a pandas-like API.
- [pands_cub](https://github.com/tdpetrou/pandas_cub) - A detailed project that teaches you how to build your own Python data analysis library, pandas_cub, from scratch.
- [fletcher](https://github.com/xhochy/fletcher) - Pandas ExtensionDType/Array backed by Apache Arrow.
- [tidypandas](https://github.com/talegari/tidypandas) - A grammar of data manipulation for pandas inspired by tidyverse.
- [redframes](https://github.com/maxhumber/redframes) - [re]ctangular[d]ata[frames]
- [static-frame](https://github.com/InvestmentSystems/static-frame) - Immutable and grow-only Pandas-like DataFrames with a more explicit and consistent interface

R
- [dplyr](https://github.com/tidyverse/dplyr) - A grammar of data manipulation, providing a consistent set of verbs that help you solve the most common data manipulation challenges.
- [data.table](https://github.com/Rdatatable/data.table) - Provides a high-performance version of base R's `data.frame` with syntax and feature enhancements for ease of use, convenience and programming speed.
- [dance](https://github.com/romainfrancois/dance) - Dancing 💃 with the stats, aka `tibble()` dancing 🕺. dance is a sort of reinvention of dplyr classic verbs, with a more modern stack underneath, i.e. it leverages a lot from vctrs and rlang.

JavaScript
- [Arquero](https://github.com/uwdata/arquero) - A JavaScript library for query processing and transformation of array-backed data tables. Following the relational algebra and inspired by the design of dplyr, Arquero provides a fluent API for manipulating column-oriented data frames.
- [dataflow-api](https://github.com/vega/dataflow-api) - JavaScript API for dataflow processing using the vega-dataflow reactive engine. Perform common database operations (sorting, filtering, aggregation, window calculations) over JavaScript objects.
- [datalib](https://github.com/vega/datalib) - A JavaScript data utility library. It provides facilities for data loading, type inference, common statistics, and string templates.
- [Tidy.js](https://github.com/pbeshai/tidy) - Tidy up your data with JavaScript, inspired by dplyr and the tidyverse.
- [Data-Forge](https://github.com/data-forge/data-forge-ts) - The JavaScript data transformation and analysis toolkit inspired by Pandas and LINQ.
- [zebras](https://github.com/nickslevine/zebras) - A data manipulation and analysis library written in JavaScript offering the convenience of pandas or R.
- [dataframe-js](https://github.com/Gmousse/dataframe-js) - A javascript library providing a new data structure for datascientists and developers.
- [Simple Data Analysis (SDA)](https://github.com/nshiab/simple-data-analysis.js) - Easy-to-use JavaScript library for most common data analysis tasks.

Julia
- [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) - Tools for working with tabular data in Julia.
- [DataKnots.jl](https://github.com/rbt-lang/DataKnots.jl) - A Julia library for querying data with an extensible, practical and coherent algebra of query combinators.
- [Volcanito.jl](https://github.com/johnmyleswhite/Volcanito.jl) - Backend agnostic for tabular data operations in Julia.
- [Query.jl](https://github.com/queryverse/Query.jl) - A package for querying julia data sources. It can filter, project, join and group data from any iterable data source, including all the sources supported in IterableTables.jl.
- [TidierData.jl](https://github.com/TidierOrg/TidierData.jl) - 100% Julia implementation of the dplyr and tidyr R packages.

Clojure
- [tech.ml.dataset](https://github.com/techascent/tech.ml.dataset) - A Clojure high performance data processing system.
- [tablecloth](https://github.com/scicloj/tablecloth) - Dataset manipulation library build on the top of tech.ml.dataset.

Common Lisp
- [Data Frame](https://github.com/Lisp-Stat/data-frame) - Data frames for Common Lisp

C++
- [DataFrame](https://github.com/hosseinmoein/DataFrame) - A C++ statistical library that provides an interface similar to Pandas package in Python.

Elixir
- [explorer](https://github.com/elixir-nx/explorer) - Explorer brings series (one-dimensional) and dataframes (two-dimensional) for fast data exploration to Elixir.

Elm
- [tidy](https://github.com/gicentre/tidy) - Leaning heavily on the principles of the tidyverse, and especially tidy data, this package makes it easy to reshape and tidy tabular data for easier data analysis and visualization.

Go
- [column](https://github.com/kelindar/column) - High-performance, columnar, in-memory store with bitmap indexing in Go.
- [gambas](https://github.com/jpoly1219/gambas) - Data analysis tool for Go. Similar to the famous Python library pandas.

Haskell
- [DataFrame](https://github.com/mchav/dataframe) - An intuitive, dynamically-typed DataFrame library.

Java
- [Tablesaw](https://github.com/jtablesaw/tablesaw) - Java dataframe and visualization library.

Kotlin
- [Kotlin Dataframe](https://github.com/Kotlin/dataframe) - Structured data processing in Kotlin.
- [krangl](https://github.com/holgerbrandl/krangl) - A {K}otlin library for data w{rangl}ing.

Lua
- [Assistant](https://github.com/coalio/Assistant) - A data science library providing flexible dataframes for Lua 5.1+

Q
- [qSQL](https://code.kx.com/q/basics/qsql/) - Query language embedded into Q.

Raku
- [Data::Reshapers](https://github.com/antononcube/Raku-Data-Reshapers) - Raku package with data reshaping functions for different data structures.

Ruby
- [rover](https://github.com/ankane/rover) - Simple, powerful data frames for Ruby.
- [daru](https://github.com/SciRuby/daru) - daru (Data Analysis in RUby) is a library for storage, analysis, manipulation and visualization of data in Ruby.
- [polars-ruby](https://github.com/ankane/polars-ruby) - Blazingly fast DataFrames for Ruby.

Rust
- [polars](https://github.com/ritchie46/polars) - A blazingly fast DataFrames library implemented in Rust.
- [datafusion](https://arrow.apache.org/datafusion/user-guide/dataframe.html) - DataFrame API in Apache Arrow DataFusion

Wolfram
- [Dataset](https://reference.wolfram.com/language/ref/Dataset.html) - Represents a structured dataset based on a hierarchy of lists and associations.

Database
- [SQLite](https://sqlite.org/index.html) - A C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine
- [DuckDB](https://github.com/cwida/duckdb) - An embeddable SQL OLAP Database Management System.

CLI
- [VisiData](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for discovering and arranging data.

GUI
- [Power Query](https://docs.microsoft.com/en-us/powerquery-m) - A core capability of Power Query is to filter and combine, that is, to mash-up data from one or more of a rich collection of supported data sources.

## Other
- [prql](https://github.com/prql/prql) - A modern language for transforming data — a simple, powerful, pipelined SQL replacement.
- [Malloy](https://github.com/looker-open-source/malloy) - An experimental language for describing data relationships and transformations.
- [Arrow](https://github.com/apache/arrow) - A cross-language development platform for in-memory data.
- [Substrait](https://github.com/substrait-io/substrait) - A cross platform way to express data transformation, relational algebra, standardized record expression and plans.
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
