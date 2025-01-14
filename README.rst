***********************************************************************
pyanthem: an audiovisualization tool to make your data more interesting
***********************************************************************

pyanthem is a Python_ tool that transforms three-dimensional time-varying datasets into a colorful, audible format. pyanthem boasts a variety of features: 

1) Raw data decomposition
2) Video and audio preview
3) A broad variety of video and audio parameters
4) Command-line reproduction via config files

Requirements
============
Python 3:
   Currently, pyanthem is tested to work on Python_ 3.6+. This will be 
   updated as more versions are tested.

pip:
   pip is needed for the installation of the pyanthem module and its
   dependencies.  Most python versions will have pip installed already, 
   see the  `pip installation`_ page for instructions if you do not 
   have pip.

git (optional):
  git_ allows pyanthem to download external audio files quickly and 
  easily.

ffmpeg (optional):
   ffmpeg_ enables merging video and audio files into a single output.

.. _Python: https://www.python.org/
.. _pip installation: https://pip.pypa.io/en/latest/installing/
.. _git: https://git-scm.com/
.. _ffmpeg: https://ffmpeg.org/

Installation
============
Basic installation using pip::

   python -m pip install pyanthem
   
Installation of "Piano" audio engine using git/GitPython::

   import pyanthem
   pyanthem.AE_download()

Usage
=====


Contributing
============

Step 1
------
- **Option 1**
    - Fork this repo!

- **Option 2**
    - Clone this repo to your local machine using 
    
    ```python
    git clone https://github.com/nicthib/pyanthem.git
    ```

Step 2
------
- Improve this repo!

Step 3
------

- Create a new pull request using `<https://github.com/nicthib/pyanthem/compare/>`_

Team
----

.. |niclogo| image:: https://avatars1.githubusercontent.com/u/34455769?v=3&s=200

.. csv-table::
   :header: Nic Thibodeaux

   |niclogo|
    `<http://github.com/nicthib>`
FAQ
---

- **How do I do *specifically* so and so?**
    - No problem! Just do this.

Support
-------
- Twitter: `@nicthibs`_

.. _`@nicthibs`: http://twitter.com/nicthibs
