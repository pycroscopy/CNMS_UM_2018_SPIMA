# Imaging and Spectral Data Analysis in Python

We present a set of jupyter notebooks and presentations that go over the
basics of:

- Image and spectral data analysis in Python 
- [USID](https://pycroscopy.github.io/pyUSID/data_format.html), [pyUSID](https://pycroscopy.github.io/pyUSID/about.html), 
  and [pycroscopy](https://pycroscopy.github.io/pycroscopy/about.html) as tools for analyzing large and multidimensional imaging / spectroscopy datasets 
    
This material was developed as part of the [2018 CNMS User Meeting](./CNMS_UM_Workshop_schedule.md)

See our [list of tutorials](https://pycroscopy.github.io/pyUSID/external_guides.html) for more information
  
## Getting started
### (Recommended) Working on your personal computer
1. (one time only) Install necessary software:
    1. Follow [these instructions](https://pycroscopy.github.io/pycroscopy/install.html) to install Anaconda + 
       pycroscopy on your own laptop
    2. Also please install pyUSID via: ``pip install pyUSID`` just like how you installed pycroscopy
2. (one time only) Download the contents of this tutorial onto your computer:
    1. click on the green ``Clone or download`` button
    2. Click on ``Download ZIP``
    3. Download the zip file to your Documents / Downloads / Desktop
    4. Unzip the zip file
3. Start up a Jupyter Notebook:
    1. Start a terminal:
        1. Windows users: Click on ``Start`` >> ``Anaconda3`` >> ``Anaconda Prompt``
        2. Mac / Linux users: Open ``Terminal``. You can find it by holding down your ``Command`` and ``Space`` key and 
           typing ``Terminal`` in the search bar that pops up.
    2. In the ``Terminal`` or ``Anaconda Prompt``, type ``jupyter notebook`` and press the ``Enter`` or ``Return`` key.
       If everything happened correctly, a new tab should pop up on your default browser showing familiar folders such 
       as ``Desktop``, ``Documents``, etc. 
    3. **Do not close the Terminal or Anaconda Prompt!**
4. Finally, work on the notebooks in this tutorial:
    1. Navigate to the folder (e.g. - ``Desktop``) where you unzipped the zip file 
       in step 2.
    2. Click on the ``index.ipynb`` file which should present a new tab on your browser that looks [like this](./index.ipynb)
5. Once you are done working on the jupyter notebooks:
    1. Go back to the ``Terminal`` or ``Anaconda Prompt``. Hold down the ``Ctrl`` (control) key and press the ``C`` key 
       twice to shut down the Jupyter server.
    2. You can now close the Jupyter browser tabs and the ``Terminal`` or ``Anaconda Prompt``
    
*We understand that this may seem a little tedious in the beginning but we assure you that you will get used to this very quickly*

### Trying out the tutorial online
If you are having trouble with installing Anaconda on your personal computer (above), please try one of the following:

- **Azure notebooks**
    1. You will need to [sign up](https://signup.live.com/?wa=wsignin1.0&rpsnv=13&ct=1533149109&rver=6.7.6643.0&wp=MBI_SSL&wreply=https%3a%2f%2faccount.microsoft.com%2fauth%2fcomplete-signin%3fru%3dhttps%253A%252F%252Faccount.microsoft.com%252F%253Frefd%253Daccount.microsoft.com%2526refp%253Dsignedout-index&id=292666&lw=1&fl=easi2&pcexp=true&uictx=me&contextid=D0A988B000A50828&bk=1533149128&uiflavor=web&uaid=098dd33703314790a45fcfb799fd93d3&mkt=EN-US&lc=1033&lic=1) for a Microsoft (Outlook, Hotmail, ...) account if you don't already have one.
    2. Once you are logged in, click [here](https://notebooks.azure.com/ssomnath/libraries/cnms2018um)
    3. Next, click on the ``Clone`` button (just above the search bar) to make your own copy of the project
    4. Once your copy of the project has been created, click on the ``Run`` button along the same line as the ``Clone`` button
    5. You should be directed to a familiar Jupyter notebook server page.
        
- **Binder**
    - The benefit of Binder is that one does not need a Microsoft account, 
      but the drawback is that your solutions / edits will be lost if you close the browser tab(s)
    - Click [here](https://mybinder.org/v2/gh/pycroscopy/pyUSID_Tutorial/master) to launch the jupyter notebook server.
      This will take a while so please be patient.
      
Finally, for either option, click [here](./index.ipynb) to get started with the notebooks

## Getting help
Please get in touch with us on our [Google group](https://groups.google.com/forum/#!forum/pycroscopy)