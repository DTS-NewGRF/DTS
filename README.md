# Korean Empty Set
**Korean Empty Set**은 한국 관련 NewGRF 세트를 위한 템플릿입니다.  
**Korean Empty Set** is a template for Korean NewGRF sets.

# Requires
You need Linux bash shell or WSL to make your NewGRF project by using this template.
And you need to deal with some git command.

# How to use
 1. Modify ``Makefile.config``. Do not modify other variables if there is no certain purpose.
    ```
    # Name
    REPO_NAME           ?= Korean Empty Set
    
    # File name of *.grf, *.tar and so on
    BASE_FILENAME       ?= ko_empty_set
    
    # Version
    VERSION             ?= $(shell ./findversion.sh)
    RECENT_UPDATED      ?= $(shell date +"%Y.%m.%d")
    REPO_BRANCH_VERSION ?= 0
    
    # Author's information
    AUTHOR_WEBSITE      ?= https://domain.com
    AUTHOR_EMAIL        ?= your_email@address.com
    
    # If needed, declare the minimum NML requirements
    REQUIRED_NML_BRANCH  = 0.4
    # MIN_NML_REVISION   = 0
    ```
    * ``REPO_NAME``: Your NewGRF name  
    * ``BASE_FILENAME``: Your NewGRF's file name
    * ``AUTHOR_WEBSITE``: NewGRF's website url
    * ``AUTHOR_EMAIL``: Author's email address
 2. Modify **_./docs/license.txt_** and **_./docs/readme.ptxt_** as you wish
 3. Rename **_ko_empty_set.pnml_** into the **_(BASE_FILENAME).grf_**  
    For example, if ``BASE_FILENAME`` is _ko_test_set_, then rename it into **_ko_test_set.grf_**.  
 4. Write your code in **_ko_test_set.pnml_**.  
    You may put some other _.pnml_ files by creating some directories, such as ``src``.  
	Then you may include it by ``#include "./src/some_file_name.pnml"`` syntax.
 5. Run ``make all`` in the shell. Then compiled **_ko_test_set.tar_** tar file generated in **_./generated/_** directory.
 6. ``make clean`` will clean your project.
 7. Version will be named as git's commit hash.  
    If the last commit has git tag, the tag name will be your NewGRF's version name.

# Build release example
```
(some git commands, such as "git add ." and "git commit")
git tag v1.0.2
make clean
make all
```
