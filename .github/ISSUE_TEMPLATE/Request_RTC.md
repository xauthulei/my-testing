---
name: Request RTC template
about: The WI template should be used to log RTC related requests.
labels: kind/bug

---

Purpose: (for what project or product and justifications): [  ]

Create a new stream based on a existing stream or snapshot:
--------------------------------------------------------------------------
   <RTC project name  such as pc-utopia, pc-ego etc>     [   ]
   <Based stream or snapshot name the new stream is cut from>     [  ]
   <New stream name>   [      ]

For the newly created stream, if we need to create directory /pcc/lsfqa-trusted/<component>_ext/shared/<stream> to put shared libs in for build
[                       ]


Create a new snapshot or baseline on a stream:
---------------------------------------------------------
   <RTC project name  such as pc-utopia, pc-ego etc>     [   ]
   <Stream name> [   ]
   <New snapshot or baseline name> [   ]


Freez/lock a stream:
------------------------
   <Stream name>  [   ]
   <Frozen period> [   ]


Create new component and new stream based on the new component:
--------------------------------------------------------------------------------------
   <RTC project name to add this new component> [     ]
   <New component name> [    ]
   <New stream name> [    ]


Migrate code module from CVS or SVN to RTC:
-------------------------------------------------------
   <CVS or SVN module and branch name(s) [     ]
   <RTC project name to migrate to  [    ]


Others (please specify):
