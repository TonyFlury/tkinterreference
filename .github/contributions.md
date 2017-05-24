# Contributing to this repository

You can contribute in two ways: 

  - you can either highlight an Error, Omission or suggest a Clarification
  - Or actually Contribute changes to the actual documentation

# To Highlight an Error, Omission or requesting Clarification of the documentation

 1. [Create a new Issue](https://github.com/TonyFlury/tkinterreference/issues)

 2. Complete the Template as accurately as possible.  
    an Issue which states that 'The Document is wrong' is unlkely to be useful.  
    Use section and sub section names to identify the location of the issue.
  
 3  Change the Label on the New Issue - Click the Gear as shown : <img alt-text='Change Label' align='middle' src='https://github.com/TonyFlury/tkinterreference/blob/master/.github/Labels.png'>  
    The Labels to be used :
   
  - **Error** : The Document is wrong/incorrect
  - **Omission** : The document is missing something
  - **Clarification** : The document isn't clear and needs to be rewritten
  - **Code Error** : There is an error in a code example
  - Do Not use **Internal**, **Invalid** or **Won't Fix** labels these are for internal use only.
   
 4 Click Submit New Issue
 
 This new Issue will be analyzed by the Author team, and the documents updated 

# To Contributing fixes

  To contribute changes to the documentation you should have the following skills : 

  - Familiarity with git & github
  - Familiarity of Restructed Text, sphinx & the sphinx-rtd-theme

  1. Fork the 'Next Release' Branch of this repository
  2. Clone the forked repository onto your local system.
  3. Add a Git remote for the original repository.
  4. Create a feature branch in which to place your changes.  
     For a single issue branch your branch should be called Issue-<Issue number>  
     For a multi Issue branch name your branch Issue-<Issue>-<Issue>-<Issue> (limit to 250 chars)  
  5. Make your changes to the new branch.
  6. Commit the changes to the branch.
  7. Push the branch to your local fork
  8. Open a [pull request](https://github.com/TonyFlury/tkinterreference/pulls) from your features branch to the this repo.
  9. Ensure you fill the pull request template correctly - (Do not fill in the 'Integrator/Merger/ section).
  10.  After your pull request is merged (delete fork & local clones etc) - Do not clean up before.
  
  Note - this repository uses a customised version of the sphinx-rtd-them theme.css file. Hopefully the fixes in this file will be
  eventually be merged into the mainline sphinx-rtd-theme repo.  
  It is not recommended that you do NOT exectue `make clean` against your clone - or if you do - capture a copy 
  of the `docs/_build/html/_static/css/theme.css` file before `make clean` and then replace it afer before doing a `make html`
  
  
