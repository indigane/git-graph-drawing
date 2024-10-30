# Git graph drawing

A collection of git graph drawing implementations. Additions and corrections welcome.

## Git

| Name | Description | Relevant code |
| ------ | ------ | ------ |
| [mlange-42/git-graph](https://github.com/mlange-42/git-graph) | A&nbsp;command&nbsp;line&nbsp;tool&nbsp;to&nbsp;visualize&nbsp;Git&nbsp;history&nbsp;graphs&nbsp;in&nbsp;a&nbsp;comprehensible&nbsp;way, following different branching models. | https://github.com/mlange-42/git-graph/blob/f9f3c73/src/graph.rs |
| [git log --graph](https://github.com/git/git/blob/master/graph.c) | The graph API is used to draw a text-based representation of the commit history. The API generates the graph in a line-by-line fashion. | https://github.com/git/git/blob/3eb4cc4/graph.c |
| [mhutchie/vscode-git-graph](https://github.com/mhutchie/vscode-git-graph) | View a Git Graph of your repository, and easily perform Git actions from the graph. Configurable to look the way you want! | https://github.com/mhutchie/vscode-git-graph/blob/4960650/web/graph.ts |
| [gitx/gitx](https://github.com/gitx/gitx) | GitX is an OS X (MacOS) native graphical client for the git version control system. | https://github.com/gitx/gitx/blob/4ea425f/Classes/git/PBGitGrapher.mm#L71 |
| [GitHub&nbsp;Network](https://web.archive.org/web/20230816152728id_/https://github.githubassets.com/assets/chunk-app_assets_modules_github_graphs_network-graph-element_ts-3c198ffa6d2a.js) | Timeline of the most recent commits to this repository and its network ordered by most recently pushed to. | [network-graph-element.ts](https://gitlab.com/-/project/45943859/uploads/550182d6b09ac975f9e880fb01f24322/network-graph-element.ts) |
| [tortoisegit/tortoisegit](https://gitlab.com/tortoisegit/tortoisegit) | TortoiseGit is a Windows Shell Interface to Git based on TortoiseSVN. It's open source and can be built entirely with freely available software. | https://gitlab.com/tortoisegit/tortoisegit/-/blob/7010ffb9/src/TortoiseProc/RevisionGraph/RevisionGraphDlgDraw.cpp#L285 |
| [gitextensions/gitextensions](https://github.com/gitextensions/gitextensions) | Git Extensions is a standalone UI tool for managing git repositories. It also integrates with Windows Explorer and Microsoft Visual Studio (2015/2017/2019). | https://github.com/gitextensions/gitextensions/blob/0d175e4/src/app/GitUI/UserControls/RevisionGrid/Graph/RevisionGraph.cs |
| [git-up/GitUp](https://github.com/git-up/GitUp) | Work quickly, safely, and without headaches. The Git interface you've been missing all your life has finally arrived. | https://github.com/git-up/GitUp/blob/eac8e20/GitUpKit/Interface/GIGraph.m#L110 |
| [gitahead/gitahead](https://github.com/gitahead/gitahead) | GitAhead is a graphical Git client designed to help you understand and manage your source code history. | https://github.com/gitahead/gitahead/blob/e710f23/src/ui/CommitList.cpp |
| [Murmele/Gittyup](https://github.com/Murmele/Gittyup) | Gittyup is a graphical Git client designed to help you understand and manage your source code history. | https://github.com/Murmele/Gittyup/blob/6f1c322/src/ui/CommitList.cpp |
| [GNOME/gitg](https://github.com/GNOME/gitg) | gitg is a graphical user interface for git. It aims at being a small, fast and convenient tool to visualize the history of git repositories. Besides visualization, gitg also provides several utilities to manage your repository and commit your work. | https://github.com/GNOME/gitg/blob/313e6ce/libgitg/gitg-lanes.vala |
| [FredrikNoren/ungit](https://github.com/FredrikNoren/ungit) | The easiest way to use git. On any platform. Anywhere. | https://github.com/FredrikNoren/ungit/blob/e376caa/components/graph/graph.js |
| [soramimi/Guitar](https://github.com/soramimi/Guitar) | Git GUI Client | https://github.com/soramimi/Guitar/blob/c7bb0f6/src/MainWindow.cpp#L2378 |
| [git-cola/git-cola](https://github.com/git-cola/git-cola) | Git Cola is a powerful Git GUI with a slick and intuitive user interface. | https://github.com/git-cola/git-cola/blob/2c8a1a4/cola/widgets/dag.py |
| [GNOME/giggle](https://gitlab.gnome.org/Archive/giggle) | Giggle is a graphical frontend for the git content tracker (think of gitk on GTK+). | https://gitlab.gnome.org/Archive/giggle/-/blob/a9ea21bb/src/giggle-graph-renderer.c |
| [KDE/Kommit](https://invent.kde.org/sdk/kommit) | Git gui client for KDE | https://invent.kde.org/search?group_id=1558&nav_source=navbar&project_id=12019&repository_ref=master&search=graphlane&search_code=true |
| [JetpackDuba/Gitnuro](https://github.com/JetpackDuba/Gitnuro) | A FOSS Git client based on (Jetbrains) Compose and JGit. | https://github.com/JetpackDuba/Gitnuro/blob/f530e48/src/main/kotlin/com/jetpackduba/gitnuro/git/graph/GraphCommitList.kt |
| [gitk](https://github.com/git/git/blob/master/gitk-git/gitk) | Displays changes in a repository or a selected set of commits. This includes visualizing the commit graph, showing information related to each commit, and the files in the trees of each revision. | https://github.com/git/git/blob/99e70f3/gitk-git/gitk#L5113 <br> https://github.com/git/git/blob/99e70f3/gitk-git/gitk#L950-L967 |
| [jonas/tig](https://github.com/jonas/tig) | Tig is an ncurses-based text-mode interface for git. It functions mainly as a Git repository browser, but can also assist in staging changes for commit at chunk level and act as a pager for output from various Git commands. | https://github.com/jonas/tig/blob/090ac86/src/graph-v1.c <br> https://github.com/jonas/tig/blob/090ac86/src/graph-v2.c |
| [tibirna/qgit](https://github.com/tibirna/qgit) | With qgit you will be able to browse revisions history, view patch content and changed files, graphically following different development branches. | https://github.com/tibirna/qgit/blob/d0a9a73/src/lanes.cpp <br> https://github.com/tibirna/qgit/blob/0e4dc81/src/listview.cpp#L987 |
| [JetBrains/intellij-community](https://github.com/JetBrains/intellij-community) | IntelliJ IDEA Community Edition & IntelliJ Platform | https://github.com/JetBrains/intellij-community/tree/1cbaf4f/platform/vcs-log/graph/src/com/intellij/vcs/log/graph <br> https://github.com/JetBrains/intellij-community/tree/e10e2af/plugins/git4idea/src/git4idea/history |
| [indigane/visual-git](https://gitlab.com/indigane/visual-git) | Open your eyes to Git. | https://gitlab.com/indigane/visual-git/-/blob/5728bc3e/frontend/js/ui/graph.js |
| [sourcegit-scm/sourcegit](https://github.com/sourcegit-scm/sourcegit) | Windows/macOS/Linux GUI client for GIT users | https://github.com/sourcegit-scm/sourcegit/blob/9bccb34/src/Models/CommitGraph.cs |

## Non-Git or Git simulations

| Name | Description | Relevant code |
| ------ | ------ | ------ |
| [liuliu-dev/CommitGraph](https://github.com/liuliu-dev/CommitGraph) | An&nbsp;interactive&nbsp;React&nbsp;component&nbsp;for&nbsp;visualizing&nbsp;commit&nbsp;log&nbsp;graphs with support for manual pagination integration. | https://www.dolthub.com/blog/2024-08-07-drawing-a-commit-graph/ |
| [nicoespeon/gitgraph.js](https://github.com/nicoespeon/gitgraph.js) | A JavaScript library to draw pretty git graphs in the browser | https://github.com/nicoespeon/gitgraph.js/tree/8856333/packages/gitgraph-core/src |
| [jmini/GitGraph4J](https://github.com/jmini/GitGraph4J) | Java code to create "git graph" images (targeting mainly the `Diagrams.net` (`*.drawio` file) output format and supporting `Mermaid` (`*.mmd` file) and `Graphviz` (`*.dot` file) outputs as well). | https://github.com/jmini/GitGraph4J/tree/b653d7f/src/main/java/fr/jmini/gitgraph4j |
| [git-school/visualizing-git](https://github.com/git-school/visualizing-git) | Visualize how common Git operations affect the commit graph | https://github.com/git-school/visualizing-git/blob/bbfabb8/js/historyview.js |
| [pcottle/learnGitBranching](https://github.com/pcottle/learnGitBranching) | An interactive git visualization and tutorial. | Please add |
| [facebook/renderdag](https://github.com/facebook/sapling/blob/aa07b28/eden/scm/lib/renderdag) | Part of Sapling. Used by [Jujutsu](https://github.com/martinvonz/jj) (`jj`) to render a git graph. | https://github.com/facebook/sapling/blob/aa07b28/eden/scm/lib/renderdag/src/render.rs |
| [mercurial/TortoiseHg](https://tortoisehg.bitbucket.io/) | TortoiseHg is a Windows shell extension and a series of applications for the Mercurial distributed revision control system. | https://foss.heptapod.net/mercurial/tortoisehg/thg/-/blob/874751aa7872779e4ffe0396d204ab8ed149a562/tortoisehg/hgqt/graph.py |

## Proprietary

*Ideas welcome for making this section more useful.*

| Name |
| ------ |
| [GitKraken](https://www.gitkraken.com) |
| [SmartGit](https://www.syntevo.com/smartgit/) |
| [Tower](https://www.git-tower.com/) |
| [Sublime Merge](https://www.sublimemerge.com/) |
| [Fork](https://git-fork.com/) |
| [Pocket Git](http://pocketgit.com/) (Android) |
| [Working Copy](https://workingcopyapp.com/) (iOS) |
| [GitDrive](http://gitdrive.com/) (iOS) |
| [PolyGit](http://www.polygitapp.com/) (iOS) |
| [Gitfox](https://www.gitfox.app/) |
| [Aurees](https://aurees.com/) |
| [GitFiend](https://gitfiend.com/) |
| [GitAtomic](https://gitatomic.bitbucket.io/Git_Tree.html) |
| [GitViewer](https://gitviewer.com/) |
| [Glint](https://glint.info/) |
| [Git Flow Chart](https://app.gfc.io/github/nvie/gitflow) |
| [gmaster](https://web.archive.org/web/20210905151822id_/https://gmaster.io/) |
| [PyCharm Log tab](https://www.jetbrains.com/help/pycharm/log-tab.html)(?) |
| [IntelliJ IDEA](https://www.jetbrains.com/help/idea/manage-branches.html)(?) |
| [Azure Repos](https://azure.microsoft.com/en-us/products/devops/repos) ([example](https://dev.azure.com/nearform/node-distro/_git/nodejs-distribution/commits)) |
