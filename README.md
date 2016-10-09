# dotfiles

My collection of dotfiles.

### gitignore
```bash
#####################################################################
# PROJECT FILES
#####################################################################


#####################################################################
# JAVASCRIPT
#####################################################################

# PACKAGE MANAGEMENT
node_modules
jspm_packages
bower_components

# TEST COVERAGE
lib-cov
coverage
build/reports
test/e2e/dist
/export

# BUILD TOOLS
.grunt
dist

# BINARY
build/Release

# LOAD TESTING
artillery_report*


#####################################################################
# PYTHON
#####################################################################
*.py[cod]
*.egg


#####################################################################
# SASS / CSS
#####################################################################
.sass-cache
*.css.map


#####################################################################
# MISCELLANEOUS FILES
#####################################################################

# DATABASE
*.sqlite*

# TEMP / CACHE
temp
.cache
*.spec
*.tmp
*~

# IDE
.idea*

# RUNTIME DATA
pids
*.pid
*.seed

# LOGS
[Ll]og*
*.log

# OS CRUFT
.DS_Store
.DS_STORE
thumbs.db

# DEVOPS
.vagrant
*.retry
```
