Performance (CPU & memory usage)
=================================

The CPU time & memory usage for running `cobind.py stat <https://cobind.readthedocs.io/en/latest/usage/stat.html>`_ between two bed file with different number of intervals.

CPU model: Intel(R) Xeon(R) Gold 6248 CPU @ 2.50GHz

.. list-table::
   :widths: 15,20,20,20
   :header-rows: 1

   * - *# of intervals in A*
     - *# of intervals in B*
     - *Real time (seconds)*
     - *Max memory (GB)*

   * - 100,000
     - 100,000
     - 7.040
     - 0.822
   * - 200,000
     - 200,000
     - 9.384
     - 0.938
   * - 300,000
     - 300,000
     - 11.798
     - 0.957
   * - 400,000
     - 400,000
     - 14.307
     - 1.002
   * - 500,000
     - 500,000
     - 16.563
     - 1.049
   * - 600,000
     - 600,000
     - 18.893
     - 1.057
   * - 700,000
     - 700,000
     - 21.599
     - 1.097
   * - 800,000
     - 800,000
     - 23.874
     - 1.146
   * - 900,000
     - 900,000
     - 27.262
     - 1.166
   * - 1,000,000
     - 1,000,000
     - 29.472
     - 1.220