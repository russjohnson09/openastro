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





python -m pip install --upgrade pip
pip install -r requirements.txt



#PyGObject
      error: Microsoft Visual C++ 14.0 is required. Get it with "Microsoft Visual C++ Build Tools": https://visualstudio.microsoft.com/downloads/



pip install pytz
pip install PyGObject
pip install PyGTK



https://github.com/Automattic/node-canvas#installation


#C++ Requirements
C++ Development Using 
 https://visualstudio.microsoft.com/downloads/
 
#Install GTK
Using the installer still getting cannot open cairo.h



https://github.com/Automattic/node-canvas/wiki/Installation:-Windows

https://github.com/tschoonj/GTK-for-Windows-Runtime-Environment-Installer/releases

      C:\Users\russ\AppData\Local\Temp\pip-install-p64jzgk4\pycairo\cairo\pycairo.h(37): fatal error C1083: Cannot open include file: 'cairo.h': No such file or directory





  python-gtk2
  python-dateutil
  python-gnome2-desktop (>= 2.16) /* for python bindings to librsvg, pyrsvg */
  python-cairo (>= 1.2.0)
  
  
  
  #pygobject
  https://pygobject.readthedocs.io/en/latest/
  
  
  C:\msys64\home\
  
  
  
  
  
  pip install PyGObject



C:\msys32\mingw64\bin\python3.exe

change python to this one?

yes use https://pygobject.readthedocs.io/en/latest/getting_started.html

with msys32 python 3 install.


Requirement already satisfied: pytz in c:\users\russ\appdata\local\programs\python\python37\lib\site-packages (2019.1)



pip install pytz



https://github.com/orlp/dev-on-windows/wiki/Installing-GCC--&-MSYS2
pacman -S --needed base-devel mingw-w64-i686-toolchain mingw-w64-x86_64-toolchain \
                    git subversion mercurial \
                    mingw-w64-i686-cmake mingw-w64-x86_64-cmake



Add C:\dev\msys64\mingw64\bin and C:\dev\msys64\mingw32\bin, in that order, to your PATH. Note that MSYS2 also puts a lot of other tools in this directory, most notably Python. So put these entries below any other tools you might have installed in your PATH.

                    
            https://github.com/mivion/swisseph
            
pip install pyswisseph


https://stackoverflow.com/questions/51654726/pip-install-pyswisseph-giving-error-on-windows-10

pyswisseph ubuntu only?

https://www.astro.com/swisseph/swephinfo_e.htm

https://www.astro.com/swisseph/swephprg.htm


https://answers.launchpad.net/openastro.org/+question/168824

https://github.com/astrorigin/pyswisseph/issues/12
 pip install pyswisseph‑2.5.1.post0‑cp37‑cp37m‑win_amd64.whl
 
 
 
 https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyswisseph
 
 
 
 
 
 
 pip install pyswisseph-2.5.1.post0-cp37-cp37m-win_amd64.whl
 
 
  pip install pyswisseph-2.5.1.post0-cp37-cp37m-win_amd64.whl
  
  
  pyswisseph‑2.5.1.post0‑cp37‑cp37m‑win_amd64.whl
  
  
  
  https://github.com/astrorigin/pyswisseph/issues/12
  
  
  
  