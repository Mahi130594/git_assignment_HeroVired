# git_assignment_HeroVired
## Q1: CalculatorPlus - Git Workflow
 * Created Repository: git_assignment_HeroVired
     * Created and Work on the dev Branch
       * Created and Switch to dev branch
       * Implementd arithmetic operations including add, subtract, multiply, and divide in calculator.py.
       * Commit and Push Changes
     * Merge dev into main & Create Release v1
       * Switched to main branch
       * Merged dev into main
       * Created a Version 1.0 Release
     * Add Collaborators
     * Feature Implementation
       * Created feature/sqrt branch
       * Implemented square_root method in calculator.py
       * Commit and Push Changes
     * Bug Fixing
       * Switched to dev branch
       * Fixed divide function to handle division by zero
       * Commit and Push Bug Fix
       * Kept feature/sqrt Updated
     * Code Review & Merging
       * Created Pull Request: Request a Code Review from a team member
       * Apply any suggested changes and push updates
     * Merge Approved PR into dev
       * After Approval, merge feature/sqrt into dev
     * Final Testing & Release v2
       * Tested in dev branch and Merge dev into main
       * Created Release Version 2.0: Added square root functionality & bug fixes

## Q2: Integrating Git LFS and Handling Large Files
  * Enables the LFS support for system and configures the Git repository to use LFS - Initialize Git LFS
  * Track specific .bin  file and Added the .gitattributes file (which stores LFS tracking rules) to Git
  * Adding & Pushing Large Files:
    * Created and switch to a new lfs branch
    * Generated a 200MB file using PowerShell
    * Add, commit and Push the branch to the repository
  * Verifying Large File on Another Machine
    * Clone the repository to my another machine
    * Navigate and Check out the lfs branch
    * Large file is downloaded
### --- File downloaded in the correct size (200MB in this case) ---

## Q3: Structured guide to implementing the Geometry Calculator in GitHub with Git branching and stash
 * Navigate to your project directory and create, switch to the geometry-calculator branch
 * Implemented Circle Area Calculation
   * Created and working on the new feature branch circle area.
   * Modified the geometry.py file and Stash the Incomplete Feature
   * Checked the current status to confirm that the changes are stashed
   * The output is clean working directory with no modified files.
* Implemented Rectangle Area Calculation
   * Created and working on the new feature branch rectangle area.
   * Modified the geometry.py file and Stash the Incomplete Feature
   * Checked the current status to confirm that the changes are stashed
   * The output is clean working directory with no modified files.
* Verified that both working directory is clean
* Switched back to the feature/circle-area branch and Retrieve the stashed changes -> add, Commit and Push the circle Area Feature
* Switched back to the feature/rectangle-area branch and Retrieve the stashed changes -> add, Commit and Push the rectangle Area Feature
* Created Pull Requests and after approval, merge both pull requests into the dev branch
* both features are tested and merged into dev and merge the dev branch into main and release the final version.
  
   
