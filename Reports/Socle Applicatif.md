PLAY [Install Base Packages]

TASK [Gathering Facts]
ok: [VM1]
ok: [VM2]

TASK [Update cache]
ok: [VM1]
ok: [VM1]

TASK [Install sudo curl wget]
changed: [VM1]
changed: [VM2]

PLAY RECAP
VM1 : ok=2 changed=1 unreachable=0 failed=0 skipped=0 rescued=0 ignored=0  
VM2 : ok=2 changed=1 unreachable=0 failed=0 skipped=0 rescued=0 ignored=0
