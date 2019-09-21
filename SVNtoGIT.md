## SVN to GIT Ideas
### The following guide helps with two topics. 
  - Effective branching strategies for your GIT
  - Steps to convert your trunk, branches and tags from SVN to GIT

### Effective branching strategies for your GIT
#### SVN Branching Strategy
  - SVN has a three folder global structure for your code base and your contents.
  - **TRUNK**
    - Developers and content owners use trunk mostly for current development. Trunk is usually lifeline development branch.
  - **BRANCH**
     - Developers move the code from trunk to branch when a its ready for testing, especially the development testing is complete. Once a code is moved from Trunk to Branch , the Branch becomes the go-live branch for the current development. All further testing happens from the release of this branch.
   - **TAGS**
     - Whenever a branch is release,the same will be tagged for future reference to the TAGS folder. Even from TRUNK tags can be obtained at any state. Content moved to tag usually stays there as a marked revision for ready to use. Usually none of the active development happens at the TAGS folder.
     
 ### SVN Release TimeLine
  - Release N - Current Development Version
  - Release N-1 - Release currently in Live and support branches.
  - Release N+1 - Upcoming Release for Development.
  
  
    




### Steps to convert your trunk, branches and tags from SVN to GIT.
  - we will be using git svn clone tool to perform the below operations.
  - you can read the second topic on branching strategy when you wish to decide 
