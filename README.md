# My Sublime Text 3 setup

## Installing
1. Install [Sublime](https://www.sublimetext.com/3).
2. Install [Package Control](https://sublime.wbond.net/installation):
   - Run Sublime. Open the console ``View > Show Console``.
   - Paste in the following:
````
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
````

3. Go to ``Packages/``. Delete ``Packages/User`` folder.
4. Clone git repo as ``Packages/User`` folder.
````
git clone https://github.com/khanil/sublime-settings.git User
````
5. Run Sublime. And wait until all packages would be installed.
   - **Ignore error messages about color schemes. They apear because all packages are not installed yet.**
