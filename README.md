
## 'std::cout << 'Hello World << std::endl;'

```mermaid
%%{init:{
        'logLevel': 'debug',
        'theme': 'base',
        'themeVariables':{
                    'commitLabelFontSize': '14px',
                    'commitLabelColor': '#ffffff',
                    'commitLabelBackground': '#000000',
                    'tagLabelFontSize': '16px',
                    'tagLabelColor': '#000000',
                    'tagLabelBackground': '#f8f8f2',
                    'tagLabelBorder': '#282a36',
                    'gitBranchLabel0': '#000000',
                    'gitBranchLabel1': '#000000',
                    'gitBranchLabel2': '#000000',
                    'gitBranchLabel3': '#000000',
                    'gitBranchLabel4': '#000000',
                    'gitBranchLabel5': '#000000',
                    'gitBranchLabel6': '#000000',
                    'gitInv5': '#ff6188',
                    'gitInv6': '#79DCE9',
                    'git0': '#ffD866',
                    'git1': '#bd93f9',
                    'git2': '#89F498',
                    'git3': '#ffb86c',
                    'git4': '#6272a4',
                    'git5': '#ff6188',
                    'git6': '#79DCE9'
                    },
        'gitGraph':{
                    'showBranches': true,
                    'showCommitLabel':true,
                    'mainBranchOrder': 1
                    }
}}%%

gitGraph
       commit id: "Birth"
       
       branch develop order: 3
       checkout develop
       commit id: "Kindergarten"
       commit id: "Primary School"
       
       checkout main
       commit id: "Start Scouting"
       
       branch scout order: 2
       checkout scout
       commit id: "Wolf Cubs"
       
       checkout develop
       commit id: "Middle School"
       
       checkout scout
       commit id: "Explorers"
       
       checkout develop
       commit id: "High School"
       
       checkout scout
       commit id: "Rovers"
       
       checkout main
       merge develop tag: "Scientific HSD"
       commit id: "Start University"
       
       branch develop2 order: 4
       checkout develop2
       commit id: "Computer Science" tag: "UNITN" type: REVERSE
       
       checkout main
       merge develop2
       
       checkout scout
       commit id: "Continue scouting"
       
       checkout main
       commit id: "Re-Start University"
       branch develop3 order: 5
       checkout develop3
       commit id: "Computer Science"
      
       
```
