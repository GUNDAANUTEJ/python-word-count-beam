# python-word-count-beam

Python word-Count instructions:
* Navigate to your python-word-count-beam directory in file explorer and open with Powershell as Admin.

* Initially check whether python is installed.
python --version

* Check whether pip is installed.
pip --version

* Upgrading pip to latest version
python -m pip install --upgrade pip

* Create an virtual environment in the directory
python -m venv C:\path\to\directory

* To activate virtual environment.
C:\path\to\directory\Scripts\activate.ps1

* Now, Download and Install Apache BEAM
python -m pip install apache-beam

* Now, create 'wordcount.py' file in the directory. Copy the Code for 'wordcount.py' from this [link](https://github.com/apache/beam/edit/master/sdks/python/apache_beam/examples/wordcount.py) . Paste it in 'wordcount.py' file.

* Create a empty text file and copy the contents from this link. Paste it in your text file.

* Run the pipeline cmd in Powershell. Replace /path/to/inputfile with your input file name. Replace /path/to/write/counts with required output file name.

* python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts

* Finally, we can find output file in directory. Open with VS Code to view.
