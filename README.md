- 👋 Hi, I’m @Demon969696
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Demon969696/Demon969696 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
RUN python3 -m pip install setuptools==71.0.3 --upgrade
Collecting setuptools==71.0.3
  Downloading setuptools-71.0.3-py3-none-any.whl (2.3 MB)
Installing collected packages: setuptools
  Attempting uninstall: setuptools
    Found existing installation: setuptools 45.2.0
    Not uninstalling setuptools at /usr/lib/python3/dist-packages, outside environment /usr
    Can't uninstall 'setuptools'. No files were found to uninstall.
Successfully installed setuptools-71.0.3

RUN curl -L -O https://github.com/dogecoin/ltc-scrypt/archive/refs/tags/v1.0.1.tar.gz  && python3 -m pip install v1.0.1.tar.gz --user
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 22946    0 22946    0     0  52388      0 --:--:-- --:--:-- --:--:-- 52388
Processing ./v1.0.1.tar.gz
Building wheels for collected packages: ltc-scrypt
  Building wheel for ltc-scrypt (setup.py): started
  Building wheel for ltc-scrypt (setup.py): finished with status 'done'
  Created wheel for ltc-scrypt: filename=ltc_scrypt-1.0.1-cp38-cp38-linux_x86_64.whl size=43354 sha256=37dffc0368965bb60eb8220116c81f36e0d074a448c781f0cc7ee33d8a6debb4
  Stored in directory: /tmp/pip-ephem-wheel-cache-j1f81kse/wheels/53/1a/a1/95759412a7392ad976630e8502efe7af5353e4e3c1a16490c5
Successfully built ltc-scrypt
Installing collected packages: ltc-scrypt
Successfully installed ltc-scrypt-1.0.1
