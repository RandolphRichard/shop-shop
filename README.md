# MegaStore

Deploy Link: https://meg-store.herokuapp.com/

## User Story

AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem

## Acceptance Criteria

GIVEN an e-commerce platform that uses Redux to manage global state
* WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
* WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
* WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
* WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
* WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API

# Screenshot:
![](./images/1.png)
![](./images/2.png)

# Personal Note
All the criteria had been met. Installed the dependencies required to run the App. It uses Redux to manage global state as asked instead of the Context API as we di on the Module. All the functiosn work perfectly fine.