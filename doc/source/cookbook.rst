.. _cookbook:

.. currentmodule:: pandas

.. ipython:: python
   :suppress:

   import numpy as np
   import random
   import os
   np.random.seed(123456)
   from pandas import *
   import pandas as pd
   randn = np.random.randn
   randint = np.random.randint
   np.set_printoptions(precision=4, suppress=True)

********
Cookbook
********

This is a respository for *short and sweet* examples and links for useful pandas recipes.
We encourage users to add to this documentation. 

This is a great *First Pull Request* (to add interesting links and/or put short code inline
for existing links)

.. _cookbook.selection:

Selection
---------

The :ref:`indexing <indexing>` docs.

`Boolean Rows Indexing
<http://stackoverflow.com/questions/14725068/pandas-using-row-labels-in-boolean-indexing>`__

`Using loc and iloc in selections
<https://github.com/pydata/pandas/issues/2904>`__

`Extending a panel along the minor axis
<http://stackoverflow.com/questions/15364050/extending-a-pandas-panel-frame-along-the-minor-axis>`__

`Boolean masking in a panel
<http://stackoverflow.com/questions/14650341/boolean-mask-in-pandas-panel>`__

`Selecting via the complement
<http://stackoverflow.com/questions/14986510/picking-out-elements-based-on-complement-of-indices-in-python-pandas>`__

.. _cookbook.multi_index:

MultiIndexing
-------------

The :ref:`multindexing <indexing.hierarchical>` docs.

`Creating a multi-index from a labeled frame
<http://stackoverflow.com/questions/14916358/reshaping-dataframes-in-pandas-based-on-column-labels>`__

Slicing
~~~~~~~

`Slicing a multi-index with xs
<http://stackoverflow.com/questions/12590131/how-to-slice-multindex-columns-in-pandas-dataframes>`__

`Slicing a multi-index with xs #2
<http://stackoverflow.com/questions/14964493/multiindex-based-indexing-in-pandas>`__

Sorting
~~~~~~~

`Multi-index sorting
<http://stackoverflow.com/questions/14733871/mutli-index-sorting-in-pandas>`__

`Partial Selection, the need for sortedness
<https://github.com/pydata/pandas/issues/2995>`__

Levels
~~~~~~

`Prepending a level to a multiindex
<http://stackoverflow.com/questions/14744068/prepend-a-level-to-a-pandas-multiindex>`__

`Flatten Hierarchical columns
<http://stackoverflow.com/questions/14507794/python-pandas-how-to-flatten-a-hierarchical-index-in-columns>`__

.. _cookbook.grouping:

Grouping
--------

The :ref:`grouping <groupby>` docs.

`Basic grouping with apply
<http://stackoverflow.com/questions/15322632/python-pandas-df-groupy-agg-column-reference-in-agg>`__

`Using get_group
<http://stackoverflow.com/questions/14734533/how-to-access-pandas-groupby-dataframe-by-key>`__

`Apply to different items in a group
<http://stackoverflow.com/questions/15262134/apply-different-functions-to-different-items-in-group-object-python-pandas>`__

`Expanding Apply
<http://stackoverflow.com/questions/14542145/reductions-down-a-column-in-pandas>`__

`Replacing values with groupby means
<http://stackoverflow.com/questions/14760757/replacing-values-with-groupby-means>`__

`Sort by group with aggregation
<http://stackoverflow.com/questions/14941366/pandas-sort-by-group-aggregate-and-column>`__

`Create multiple aggregated columns
<http://stackoverflow.com/questions/14897100/create-multiple-columns-in-pandas-aggregation-function>`__

Expanding Data
~~~~~~~~~~~~~~

`Alignment and to-date
<http://stackoverflow.com/questions/15489011/python-time-series-alignment-and-to-date-functions>`__

`Rolling Computation window based on values instead of counts
<http://stackoverflow.com/questions/14300768/pandas-rolling-computation-with-window-based-on-values-instead-of-counts>`__

Splitting
~~~~~~~~~

`Splitting a frame
<http://stackoverflow.com/questions/13353233/best-way-to-split-a-dataframe-given-an-edge/15449992#15449992>`__

.. _cookbook.pivot:

Pivot
~~~~~
The :ref:`Pivot <reshaping.pivot>` docs.

`Partial sums and subtotals
<http://stackoverflow.com/questions/15570099/pandas-pivot-tables-row-subtotals/15574875#15574875>`__

`Frequency table like plyr in R
<http://stackoverflow.com/questions/15589354/frequency-tables-in-pandas-like-plyr-in-r>`__

Timeseries
----------

`Between times
<http://stackoverflow.com/questions/14539992/pandas-drop-rows-outside-of-time-range>`__

`Vectorized Lookup
<http://stackoverflow.com/questions/13893227/vectorized-look-up-of-values-in-pandas-dataframe>`__

.. _cookbook.resample:

Resampling
~~~~~~~~~~

The :ref:`Resample <timeseries.resampling>` docs.

`TimeGrouping of values grouped across time
<http://stackoverflow.com/questions/15297053/how-can-i-divide-single-values-of-a-dataframe-by-monthly-averages>`__

`TimeGrouping #2
<http://stackoverflow.com/questions/14569223/timegrouper-pandas>`__

`Resampling with custom periods
<http://stackoverflow.com/questions/15408156/resampling-with-custom-periods>`__

`Resample intraday frame without adding new days
<http://stackoverflow.com/questions/14898574/resample-intrday-pandas-dataframe-without-add-new-days>`__

`Resample minute data
<http://stackoverflow.com/questions/14861023/resampling-minute-data>`__

.. _cookbook.merge:

Merge
-----

The :ref:`Concat <merging.concatenation>` docs. The :ref:`Join <merging.join>` docs.

`emulate R rbind
<http://stackoverflow.com/questions/14988480/pandas-version-of-rbind>`__

`Self Join
<https://github.com/pydata/pandas/issues/2996>`__

`How to set the index and join
<http://stackoverflow.com/questions/14341805/pandas-merge-pd-merge-how-to-set-the-index-and-join>`__

`KDB like asof join
<http://stackoverflow.com/questions/12322289/kdb-like-asof-join-for-timeseries-data-in-pandas/12336039#12336039>`__

`Join with a criteria based on the values
<http://stackoverflow.com/questions/15581829/how-to-perform-an-inner-or-outer-join-of-dataframes-with-pandas-on-non-simplisti>`__

.. _cookbook.plotting:

Plotting
--------

The :ref:`Plotting <visualization>` docs.

`Make Matplotlib look like R
<http://stackoverflow.com/questions/14349055/making-matplotlib-graphs-look-like-r-by-default>`__

`Setting x-axis major and minor labels
<http://stackoverflow.com/questions/12945971/pandas-timeseries-plot-setting-x-axis-major-and-minor-ticks-and-labels>`__

Data In/Out
-----------

.. _cookbook.csv:

CSV
~~~

The :ref:`CSV <io.read_csv_table>` docs

`read_csv in action
<http://wesmckinney.com/blog/?p=635>`__

`Reading a csv chunk-by-chunk
<http://stackoverflow.com/questions/11622652/large-persistent-dataframe-in-pandas/12193309#12193309>`__

`Reading the first few lines of a frame
<http://stackoverflow.com/questions/15008970/way-to-read-first-few-lines-for-pandas-dataframe>`__

`Inferring dtypes from a file
<http://stackoverflow.com/questions/15555005/get-inferred-dataframe-types-iteratively-using-chunksize>`__

`Dealing with bad lines
<https://github.com/pydata/pandas/issues/2886>`__

.. _cookbook.sql:

SQL
~~~

The :ref:`SQL <io.sql>` docs

`Reading from databases with SQL
<http://stackoverflow.com/questions/10065051/python-pandas-and-databases-like-mysql>`__

.. _cookbook.excel:

Excel
~~~~~

The :ref:`Excel <io.excel>` docs

`Reading from a filelike handle
<http://stackoverflow.com/questions/15588713/sheets-of-excel-workbook-from-a-url-into-a-pandas-dataframe>`__

.. _cookbook.hdf:

HDFStore
~~~~~~~~

The :ref:`HDFStores <io.hdf5>` docs

`Simple Queries with a Timestamp Index
<http://stackoverflow.com/questions/13926089/selecting-columns-from-pandas-hdfstore-table>`__

`Managing heteregenous data using a linked multiple table hierarchy
<https://github.com/pydata/pandas/issues/3032>`__

`Merging on-disk tables with millions of rows
<http://stackoverflow.com/questions/14614512/merging-two-tables-with-millions-of-rows-in-python/14617925#14617925>`__

`Large Data work flows
<http://stackoverflow.com/questions/14262433/large-data-work-flows-using-pandas>`__

`Troubleshoot HDFStore exceptions
<http://stackoverflow.com/questions/15488809/how-to-trouble-shoot-hdfstore-exception-cannot-find-the-correct-atom-type>`__

Storing Attributes to a group node

.. ipython:: python

    df = DataFrame(np.random.randn(8,3))
    store = HDFStore('test.h5')
    store.put('df',df)

    # you can store an arbitrary python object via pickle
    store.get_storer('df').attrs.my_attribute = dict(A = 10)
    store.get_storer('df').attrs.my_attribute

.. ipython:: python
   :suppress:

    store.close()
    os.remove('test.h5')

Miscellaneous
-------------

The :ref:`Timedeltas <timeseries.timedeltas>` docs.

`Operating with timedeltas
<https://github.com/pydata/pandas/pull/2899>`__

Aliasing Axis Names
-------------------

To globally provide aliases for axis names, one can define these 2 functions:

.. ipython:: python

   def set_axis_alias(cls, axis, alias):
        if axis not in cls._AXIS_NUMBERS:
            raise Exception("invalid axis [%s] for alias [%s]" % (axis, alias))
        cls._AXIS_ALIASES[alias] = axis

   def clear_axis_alias(cls, axis, alias):
        if axis not in cls._AXIS_NUMBERS:
            raise Exception("invalid axis [%s] for alias [%s]" % (axis, alias))
        cls._AXIS_ALIASES.pop(alias,None)


   set_axis_alias(DataFrame,'columns', 'myaxis2')
   df2 = DataFrame(randn(3,2),columns=['c1','c2'],index=['i1','i2','i3'])
   df2.sum(axis='myaxis2') 
   clear_axis_alias(DataFrame,'columns', 'myaxis2')
