# Oracle Jet

This is Oracle Jet training based on what we did in Oracle Summer Camp 2018. Go to the `TRAINING.md` and you can follow the instructions. 

Also there are public in this github link: 
[https://github.com/geertjanw/ojet-training/blob/master/README.md](https://github.com/geertjanw/ojet-training/blob/master/README.md)

The Code is resolve in this folder, but is not complete, remains the internationalization: 
[https://github.com/geertjanw/ojet-training/tree/master/result](https://github.com/geertjanw/ojet-training/tree/master/result)

There is a fix on the CRUD part updating the salary, because it expect a number and you are passing a string, check the `self.updateFields` inside `dashboard.js` to check it.

## Instructions

1. Clone the repo: `git clone https://github.com/bpmsoasolutions/oraclejet-summercamp2018.git`
2. Go to the folder
3. Launch `npm install` Note: In windows you should enter to the `mock` folder and `EmployeeManager` folder and make `npm install` in this 2 folders
4. Run `npm start` and it should up `mock-server` and oracle jet cli with the app
5. Have fun

Note: Plaese, have 2 terminals, one is running the `npm start` (mock and app), on antoher terminal go to directly to the app folder to run `ojet cli` commands when is needed
