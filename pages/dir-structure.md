# Ubooquity directory structure
```
Ubooquity
│   preferences.json    ──>  The preferences you set up on the admin page (directories, users, etc.) 
│   ubooquity─5.mv.db   ──>  The Database containing the list and metadata of your comics and ebooks
│   Ubooquity.jar       ──>  The jar you download from the Ubooquity web site
│   webadmin.cred       ──>  Encrypted admin password (delete it to reset the admin password)
│   
└────cache                
│   └───books           ──>  Covers of scanned ebooks
│   │      10.jpg
│   │      100.jpg
│   │      101.jpg
│   │      102.jpg
│   │      103.jpg
│   │      104.jpg
│   │      105.jpg
│   │      ... 
│   │
│   └───comics          ──>  Covers of scanned comics
│           10.jpg
│           100.jpg
│           101.jpg
│           102.jpg
│           103.jpg
│           104.jpg
│           105.jpg
│           ...
│           
└────fonts              ──>  Fonts used by the online ebook reader
│       Charis SIL.css
│       CharisSIL─B.woff
│       ...
│       
└────logs               ──>  Logs generated by Ubooquity
│       ubooquity.log
│       ...
│       
└───themes              ──>  User themes directory
        modern
        ...
```