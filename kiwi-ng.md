compileall of python
- compileall is compile py to pyc
- python3 -m compileall pyc -b

move to linux base
- mv pyc xxx/configuration/root/root
- move cli to linux
  - mv cli/* xxx/configuration/root/sbin/
  - chmod 755 xxx/configuration/root/sbin/
  - chmod 755 xxx/configuration/root/usr/lib/systemd/system/*
  - chmod 755 xxx/configuration/root/usr/share/xxinit/*
  - cd ..

build live os
- kiwi-ng --debug --profile XX_live_SLE_15 --type iso system build --description xxx/configuration --target-dir ${Dir_Output}
- cp -af ${Dir_Output}

wiki
- https://documentation.suse.com/appliance/kiwi-9/single-html/kiwi/index.html
- 
