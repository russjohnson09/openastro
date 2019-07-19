# openastro

##python
https://github.com/BurntSushi/nfldb/wiki/Python-&-pip-Windows-installation




https://www.openastro.org/?Download#Ubuntu



https://bootstrap.pypa.io/get-pip.py


python get-pip.py

Add c:\Python27\Scripts
to path



dependencies:
  python-gtk2
  python-dateutil
  python-gnome2-desktop (>= 2.16) /* for python bindings to librsvg, pyrsvg */
  python-cairo (>= 1.2.0)
  librsvg2-bin (for rsvg-convert binary)
  imagemagick /* export features */
  pyswisseph /* http://pyswisseph.atarax.org/ */
  openastro.org-data
  
  
  
  installation: 
     sudo setup.py install
  
  running the program:
     openastro
     
     
error: can't copy 'locale\templates\LC_MESSAGES\openastro.mo': doesn't exist or not a regular file



https://pypi.org/project/PyGTK/
pip install PyGTK

ImportError: No module named pytz


#Requirements
 Could not import dsextras module: Make sure you have installed pygobject

    error: Microsoft Visual C++ 9.0 is required. Get it from http://aka.ms/vcpython27


pip install pytz
pip install PyGObject
pip install PyGTK

pip freeze > requirements.txt
    from gi import require_version
ImportError: No module named gi


cd openastro.org-1.1.57

python openastro

python openastro.org-1.1.57/openastro 







https://www.openastro.org/?Download
python3-dateutil
gir1.2-rsvg-2.0
gir1.2-gtk-3.0
python3-tz
python3-dev
python3-cairo
imagemagick
librsvg2-bin



curl -L "http://www.openastro.org/download.php?file=source&type=python3-swisseph" | tar xz 

cd python3-swisseph-2.00.00 && sudo python3 setup.py install 

curl -L "http://www.openastro.org/download.php?file=source&type=openastro" | tar xz 

cd openastro.org-1.1.57 && sudo python3 setup.py install --prefix=/usr 

curl -L "http://www.openastro.org/download.php?file=source&type=data" | tar xz 

cd openastro.org-data-1.9 && sudo python3 setup.py install --prefix=/usr





https://datascience.com.co/how-to-install-python-2-7-and-3-6-in-windows-10-add-python-path-281e7eae62a


https://stackoverflow.com/questions/40832533/pip-or-pip3-to-install-packages-for-python-3


pip --version



C:\Users\russ\AppData\Local\Programs\Python\Python37


C:\Users\russ>pip -V
pip 19.0.3 from c:\users\russ\appdata\local\programs\python\python37\lib\site-packages\pip (python 3.7)


move python 2 to the bottom of the path






