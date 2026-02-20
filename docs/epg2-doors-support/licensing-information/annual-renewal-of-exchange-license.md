# Annual Renewal of eXchange License

1\. Created feature Branch from develop

2\. develop branch has viewDefinition.inc, BusinessLogicAtv.inc, TabAtv.inc files - PET-5701 which has not planned for release so I have reverted these files same as master

3\. Later created the pull request for the same to merge this branch to master

4\. The pull request has been approved and the develop branch is same as master now.

Steps (1-4) is not mandatory to perform and we have to do this if develop branch is not same as master

5\. Created feature Branch from develop - Bitbucket - XC DOORS Scripts repository

6\. We have check in customerInfo.inc & version.inc files to feature Branch

7\. We have used commands sd doors-lr to test it locally in VDI

8\. Later created the pull request for the same to merge this feature branch to develop

10\. The pull request has been approved and the same has merged to develop

11\. Checkout to develop branch

12\. We have used commands sd test-release to deploy scripts to test ISM profiler folder

13\. Later created the pull request for the develop to master

14\. The pull request has been approved and the same has merged to master

15\. Created tag





15\. We have used commands sd release to deploy scripts to ISM profiler folder

16\. After release below information has to available.
