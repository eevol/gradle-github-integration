# gradle-github-interation

Script to use to download GITHUB.release Assets

Use fill out fields
 
 - String defaultToken // Access token to Github User
 - String defaultOrganization // Organizatio of Repo or User
 - String defaultRepository // Repo


You can also set these properties as SYSTEM porpoerties for use in Jenkins

### Usage

 - task LIST
 List all releases that can be downloaded

 - task download -Pdownload=ID
 Download Assets of releases (not source code) with ID
