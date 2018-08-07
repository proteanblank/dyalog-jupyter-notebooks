# [Jupyter](http://jupyter.org/) notebooks for [Dyalog APL](https://www.dyalog.com/)

## What is a Jupyter notebook?

A Jupyter notebook document combines an interactive coding session with narrative text according to [Donald Knuth's *literate programming*](https://en.wikipedia.org/wiki/Literate_programming) paradigm. This format is advantageous for teaching APL, explaining algorithms, and sharing ideas. The consumer of a notebook can modify the code and see the effects of their modification, but can also modify the running text and republish the notebook.

Jupyter notebook documents can be used in the following ways:
1. Offline, on the user's local machine: This requires installing Jupyter (a Python program, so installation of Python is required as well) and [an appropriate language kernel](https://github.com/Dyalog/dyalog-jupyter-kernel).
1. Online, in a dedicated sandboxed environment. Dyalog APL Jupyter notebooks can for example be used on [TryAPL](https://tryapl.org/) with no installation necessary. Note however, that to protect the server and ensure a consistent experience, restrictions on the code apply.
1. Statically, in that a notebook can be viewed by most any general Jupyter notebook viewer (including online viewers which do not require installation).
1. Exported to any of a number of widely supported formats, for example HTML or PDF, which may then be used accordingly.

## Offline usage

1. Follow the [installation instructions for the Dyalog APL Jupyter kernel](https://github.com/Dyalog/dyalog-jupyter-kernel#installation).
1. [Download this repository](https://github.com/Dyalog/dyalog-jupyter-notebooks/archive/master.zip) and extract it to your Documents folder (on Windows) or home directory (on Linux and macOS) or a subdirectory thereof.
1. Start Jupyter Noteboook:  
Windows: Launch *Jupyter Notebook* from your start menu  
Linux and macOS: From a command line, navigate to your home directory, then run `jupyter-notebook`.
1. This should open a directory view in your browser. Navigate to and click on the notebook you want to open. 

### APL keyboard and language bar

You can get an APL language bar and enable key-bindings and character compositions using just a [a bookmarklet](https://abrudz.github.io/lb/apl) (a browser bookmark that contains commands which add new features to the browser). After adding the bookmarklet to your language bar, and opening a Jupyter notebook document in your browser, click on the bookmarklet.

## Online usage<sup>Coming soon!</sup>

1. Click on [TryAPL](https://tryapl.org/)'s **Learn** tab.
1. Select tutorial or enter the URL of an online Jupyter notebook document.<sup>Coming soon!</sup>

## Static usage

Go to https://nbviewer.jupyter.org/ and enter the address of any Jupyter notebook to render it right in your browser. No installation of anything is required. Please note that when viewed like this, the content of the notebook may not be modified, so no experimentation is allowed.

## Export to other formats

1. Follow the [instructions for offline usage](#offline-usage).
1. Open the *File* menu, click on *Download as* and select format. Note that some target formats may require installation of third party tools.

## Contributing

Feel free to contribute additional notebooks to our collection through emailing notebooks@dyalog.com or submitting [pull requests](https://help.github.com/articles/about-pull-requests/).
