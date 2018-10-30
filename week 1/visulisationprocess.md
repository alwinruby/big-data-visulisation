### Visualisation process


There are three main stages in the visualisation process:

1. Question formulation

  Once we have defined the question we want to answer, we can choose the visualisation techniques that best address the defined problem.

We can create a:

    * map to show geospatially enabled data

    * two-dimensional (2D) plot to represent relationships

    * network to visualise connections between data points.


2. Data preparation

  Many organisations already know how to manage and analyse data that are familiar to them. For example:

    * geospatial people or land and environment scientists know how to manage and acquire satellite data

    * hospitals know how to manage and acquire computed tomography (CT) or magnetic resonance imaging (MRI) scans

    * business analysts may know how to analyse social media data

    * statisticians may build network models and use visualisation to understand data flows.

Once we have the data, we need to organise it, group it, and extract specific information we wish to visualise.

Some data issues that need to be considered:

  * Do we have noisy data? Is it good quality? Do we need to remove outliers?

  * Do we have missing data? Will we fill the gaps or remove affected parts of the dataset?

  * Are the data regular or irregular? For example, if the data correspond to an irregular grid, should they be displayed this way or should the missing grid points be interpolated?

  * Do we have too much data? If so, how do we reduce the quantity of data? If we do this, we need to ensure we maintain the integrity of the data. Some possibilities here are to omit every n-th sample point, calculate averages over subsets of data, or extract data that corresponds to a particular feature (for example, a certain time period).

  * Is the data high-dimensional? We can easily visualise two or three-dimensional data (3D), but higher dimensions require special techniques. Alternatively we can display lower dimensional slices of the data; for example, it’s often useful to extract 2D slices from 3D data.

  * Do we want to display the raw data or calculated quantities? Sometimes new variables need to be calculated (using some of the given data values), and it’s these variables that are used in the visualisation.

3. Developing a visual representation

The final step in the process is to determine ways to represent the data visually so the audience understands clearly what’s being communicated. There are many factors to consider in this step. For instance some important considerations are:


* size and colour

* displays of time and location

* dimensionality, for example
    * 2D data is a simple visual presentation that maps two dimensional points (x, y) in a 2D plane. If we map a large number of points, a visual pattern can be revealed. Some 2D data representations include: xy-plots, scatter plots, bar charts, pie charts and histograms

    * 3D can be represented by: contouring, surface plots, volumetric plots and scatter plots

* complexity: faithful representation of the data or infographics.

* And of course, as we discussed at the beginning of this course, the representation will also depend on whether the purpose is:

* information visualisation

* scientific visualisation

* analytics.
