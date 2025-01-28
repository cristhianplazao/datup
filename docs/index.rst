.. datup documentation master file, created by
   sphinx-quickstart on Thu Jun 11 19:06:16 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Datup
=================================

The version of this library and document

How is it work?
---------------
::

      import datup as dt

To Instance the Class
---------------------
::

      ins = dt.Datup("aws_acces_key_id","aws_secret_access_key","datalake","logger")

Is necessary invoke all time the instance object?
-------------------------------------------------
Yes, is necessary invoke all time the instance object since, the functions must
write in /tmp/ log file as default. In documentation will find how to use the class
and change default values.

Example of a method with the callable instance
----------------------------------------------
::

      dt.check_data_format(ins,dataframe)

Can I test my updates?
----------------------
Yes, there is a file called _testing.ipynb where you can test your changes. The variables, 
must be initialized always for modularity.

Where can I find some documentation?
------------------------------------
You can find the documentation in the next address: http://18.234.95.22/
Documentation as the library is on beta mode, for that reason write to cristhianpo@datup.ai for
whatever bug

.. toctree::
   :hidden:

   modules

   datup.core
   datup.io
   datup.preparation
   datup.timeseries
   datup.utils


