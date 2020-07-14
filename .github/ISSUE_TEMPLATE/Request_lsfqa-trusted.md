---
name: Request lsfqa-trusted template
about: The template should be used to request updating /pcc/lsfqa-trusted where we
  stored the 3rd party SW for product build
title: ''
labels: Request_Lsfqa-trusted
assignees: 'xauthulei'

---

<!-- Please use this template while filing an issue to highlight technical debt to be paid down, or friction to be reduced -->

We should fill the following template to request updating /pcc/lsfqa-trusted

1. For what project or product   [     ]
--------------------------------------

2. Are the libs for Windows build, and need to be synced to Windows build env? [  ]
------------------------------------------------------------------------------------------------

3. File or directory changes [  ]
----------------------------------
  <file or directory on /pcc/lsfqa-trusted>  [     ]
  <where new files are copied from> [     ]
  (Please put the files into a shared NFS directory where we can copy from such as  /pcc/xxx/... or your $HOME/xxx/)

  New files introduced are:
3.1 our own code   [  ]
3.2 3rd-party      [  ] 
3.3 others         [  ]

  Location of updated readme [      ] 
  (Should provide this for3rd-party SW. You can find a readme template from /pcc/lsfqa-trusted/blue/3rdparty/readme.template)


4. Add new symlink [  ]
----------------------------
  <SYMLINK NAME>     [     ]
  <SYMLINK LOCATION> [     ]


5. Others and additional info to help build team  [     ]
---------------------------------------------------------
