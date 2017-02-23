## 2 Test Cases

*This section should be the core of this document. You should provide a table of test cases, one per row. For each test case, the table should provide its purpose, the steps necessary to perform the test, the expected result, the actual result (to be filled later), pass/fail information (to be filled later), and any additional information you think is relevant.*

###2.1 Unit Testing

| ID  |  Purpose | Steps |Expected Result| Actual Result|Pass/Fail |Additional Information|
|---|---|---|---|---|---|---|
| T1 |Check add player function |1.Go to TournmentManager class 2. Enter user info using addPlayersToSystem(TournamentPlayer)  3. Verify player info in database | Successfully add player | | | |
| T2  |Check remove Player function |1.Go to TournmentManager class 2. Remove user info using removePlayerFromSystem(TournamentPlayer)  3. Verify player info in database |Sucessfully remove player | | | |
| T3  | Check display historical profits function | 1.Go to TournmentManager class 2. Display all profits by time using displayHistoricalProfits 3. Verify profits in database | correct profits in time order | | | |
| T4  | Check display profits by totals function  | 1.Go to TournmentManager class 2. Display all profits by amount using displayProfitsByTotals 3. Verify total profits in database | correct total profits in order  | | | |
| T5 | Check display single player's prizes function | 1.Go to TournmentManager class 2. Display player's prizes using displaySinglePlayerPrizes 3. Verify player's prizes in database | correct player's prizes  | | | |
| T6  | Check display players' respective total prizes function   | 1.Go to TournmentManager class 2. Display player's prizes by total using getAllPlayersTotals 3. Verify player's prizes in database  | correct order of players' prizes in total  | | | |
| T8  | Check get tournament function  | 1.Go to Tournament class 2. Get a tournament using getTournament 3. Verify tournament | successfully get tournament | | | |
| T9  | Check start tournament function | 1.Go to Tournament class 2. Start a tournament using startTournament 3. Verify tournament status | Successfully start tournament | | | |
| T10  | Check end tournament function | 1.Go to Tournament class 2. End a tournament using endTournament 3. Verify tournament status  |  Successfully end tournament    | | | |
| T12| Check view matches function  | 1.Go to Tournament class 2. View all matches using viewMatchList  3. Verify matches  |  Display matches| | | |
| T13| Check get house profit function  |1.Go to Tournament class 2. Display the house profit by using getHouseProfit 3. Verify house profit   |correct house profit  | | | |
| T16| Check start match function  | 1.Go to Match class 2. Start a match using startMatch   3. Verify match  | Correct match  | | | |
| T17| Check end match function | 1.Go to Match class 2. Start a match using startMatch   3. Verify match  | Successfully get winner  | |  | |
| T22| Check display player list and all prizes function   | 1.Go to TournamentPlayer class 2. View player's username and prizes using viewPlayerTotalPrizes 3. Verify info  | Successfully display play list and prizes | | | |
| T23| Check display player list and each player's total prize function   | 1.Go to TournamentPlayer class 2. View player's username and his total prize using getAllPlayersTotals 3. Verify info | Successfully display play list and total prize  | | | |



###2.2 Integration Testing
| ID  |  Purpose | Steps |Expected Result| Actual Result|Pass/Fail |Additional Information|
|---|---|---|---|---|---|---|
| T1 | Check flow of data into database with TournmentManager class and TournamentPlayer class  | 1.Go to TournmentManager class 2. Use function addPlayersToSystem with data from TournamentPlayer class passed in 3. Verify player info in database | The player info exists in database | | | |
| T2  | Check data removal from database with TournmentManager class and TournamentPlayer class | 1.Go to TournmentManager class 2. Remove player info using removePlayerFromSystem with TournamentPlayer passed in  3. Verify player info in database | The player info doesn't exist in database | | | |
| T7  | Check flow of data into Tournament class  | 1.Go to TournmentManager class 2. Create a tournament by calling tournament class 3. Pass in TournamentPlayer list into setTournament function  4. Verify the tournament initial state | Initial info of tournament should be correct |  | | |
| T11  | Check flow of data into database with TournmentManager class, tournament class, SingleEliminationAlgorithm class, and TournamentPlayer class | 1.Go to TournmentManager class 2. Generate all matches using generateMatches with info from TournamentPlayer passed in  3. Verify matches in database | Matches info correctly exist in database  | | | |
| T13| Check flow of data between Tournament class and CalculationAlgorithm class  | 1.Go to Tournament class 2. Calling calculatePrizesProfits method in CalculationAlgorithm class by passing relevent info 3. Verify house profit  | correct house profit  | | | |
| T18| Check data flow into database between SystemDatabase class and database class| 1.Go to SystemDatabase class 2. Add some info to database using addToDatabase   3. Verify info  | Correct info in database   | | | |
| T19| Check data removal from database between SystemDatabase class and database class  | 1.Go to SystemDatabase class 2. Remove some info from database using removeFromDatabase 3. Verify info in database | Successfully remove the info from database | | | |
| T20| Check update in database between SystemDatabase class and database class | 1.Go to SystemDatabase class 2. Update some info in database using updateInDatabase 3. Verify info in database | Successfully update the info in database  | | | |
| T21| Check data flow out from database between SystemDatabase class and database class| 1.Go to SystemDatabase class 2. Get some info in database using getDataFromDatabase 3. Verify data  | Sucessfully get the data | | | |

###2.3 System Testing
| ID  |  Purpose | Steps |Expected Result| Actual Result|Pass/Fail |Additional Information|
|---|---|---|---|---|---|---|
| S1 | Check Customer Login with valid Data | 1. Choose character 2. Enter UserId 3. Enter Password 4. Click SignIn| User should Login into application |   | | |
| S2 | Check Customer Login with invalid Data  | 1. Choose character 2. Enter UserId 3. Enter Password 4. Click SignIn| User should not Login into application |   | | |
| S3 | Check UI display | 1. Login as a character 2. Click on any display botton available on the screen 3. Verify the results| Display correct info on the screen|   | | |
| S4 | Check UI input | 1. Login as a character 2. Input data on any input box available on the screen 3. Verify the results | Results shoud match our prepared sample data |  | | |




###2.4 User Acceptance Testing

