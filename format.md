## 2 Test Cases

*This section should be the core of this document. You should provide a table of test cases, one per row. For each test case, the table should provide its purpose, the steps necessary to perform the test, the expected result, the actual result (to be filled later), pass/fail information (to be filled later), and any additional information you think is relevant.*

###2.1 Unit Testing

| ID  |  Purpose | Steps |Expected Result| Actual Result|Pass/Fail |Additional Information|
|---|---|---|---|---|---|---|
| T1 |Check add player function |1.Go to TournmentManager class 2. Enter user info using addPlayersToSystem(TournamentPlayer)  3. Verify user info in database | The player info exists in database | | | |
| T2  |Check remove Player function |1.Go to TournmentManager class 2. Remove user info using removePlayerFromSystem(TournamentPlayer)  3. Verify user info in database |The player info doesn't exist in database | | | |
| T3  | Check display historical profits function | 1.Go to TournmentManager class 2. Display all profits by time using displayHistoricalProfits 3. Verify profits in database | correct profits in time order | | | |
| T4  | Check display profits by totals function  | 1.Go to TournmentManager class 2. Display all profits by amount using displayProfitsByTotals 3. Verify total profits in database | correct total profits in order  | | | |
| T5 | Check display single player's prizes function | 1.Go to TournmentManager class 2. Display player's prizes using displaySinglePlayerPrizes 3. Verify player's prizes in database | correct player's prizes  | | | |
| T6  | Check display players' respective total prizes function   | 1.Go to TournmentManager class 2. Display player's prizes by total using getAllPlayersTotals 3. Verify player's prizes in database  | correct order of players' prizes in total  | | | |
| T8  | Check get tournament function  | 1.Go to Tournament class 2. Get a tournament using getTournament 3. Verify tournament | successfully get tournament | | | |
| T9  | Check start tournament function | 1.Go to Tournament class 2. Start a tournament using startTournament 3. Verify tournament status | Successfully start tournament | | | |
| T10  | Check end tournament function | 1.Go to Tournament class 2. End a tournament using endTournament 3. Verify tournament status  |  Successfully end tournament    | | | |
| T12| Check view matches function  | 1.Go to Tournament class 2. View all matches using viewMatchList  3. Verify matches  |  Display matches| | | |
| T16| Check start match function  | 1.Go to Match class 2. Start a match using startMatch   3. Verify match  | Correct match  | | | |
| T17| Check end match function | 1.Go to Match class 2. Start a match using startMatch   3. Verify match  | Successfully get winner  | |  | |
| T22| Check display player list and all prizes function   | 1.Go to TournamentPlayer class 2. View player's username and prizes using viewPlayerTotalPrizes 3. Verify info  | Successfully display play list and prizes | | | |
| T23| Check display player list and each player's total prize function   | 1.Go to TournamentPlayer class 2. View player's username and his total prize using getAllPlayersTotals 3. Verify info | Successfully display play list and total prize  | | | |



###2.2 Integration Testing
| ID  |  Purpose | Steps |Expected Result| Actual Result|Pass/Fail |Additional Information|
|---|---|---|---|---|---|---|
| T1 |Check add player function |1.Go to TournmentManager class 2. Enter user info using addPlayersToSystem(TournamentPlayer)  3. Verify user info in database | The player info exists in database | | | | |
| T2  |Check remove Player function |1.Go to TournmentManager class 2. Remove user info using removePlayerFromSystem(TournamentPlayer)  3. Verify user info in database |The player info doesn't exist in database | | | | |

| T7  | setTournament  |  |  | | | | |
| T11  | Check generate matches function |1.Go to Tournament class 2. Generate all matches using generateMatches  3. Verify matches | Successfully generate matches |  | | | | |
| T13| Check get house profit function  |1.Go to Tournament class 2. Display the house profit by using getHouseProfit 3. Verify house profit   |correct house profit  | | | | |
| T14|  generateMatches  |  |  | | | | |
| T15| calculatePrizesProfits  |  |  | | | | |

| T18| Check add to database function | 1.Go to SystemDatabase class 2. Add some info to database using addToDatabase   3. Verify info  | Correct info in database   | | | |
| T19| Check remove from database function  | 1.Go to SystemDatabase class 2. Remove some info from database using removeFromDatabase 3. Verify info in database | Successfully remove the info from database | | | |
| T20| Check update to database function | 1.Go to SystemDatabase class 2. Update some info in database using updateInDatabase 3. Verify info in database | Successfully update the info in database  | | | |
| T21| Check get data from database function  | 1.Go to SystemDatabase class 2. Get some info in database using getDataFromDatabase 3. Verify data  | Sucessfully get the data | | | |

| ID  | Test Area | Scenario | Purpose | Steps |Expected Result| Actual Result|Pass/Fail |Additional Information|
|---|---|---|---|---|---|---|---|---|
| D1 | Functional | Add player | Add new player to application  |   | | | | |
| D2 | Functional | Remove player | Remove existing player from datastore |    | | | | |
| D3 | Functional | Set result | End tournament early and set result of the match, save it in the system  |   | | | | |
| D4 | Functional | Login | Verify Login |  | | | | |
| T24  | UI  | Login Sequence  |  Verify screen flow from login screen to initial display screen | Login     to application, verify initial screen display | | | | |

###2.3 System Testing

###2.4 User Acceptance Testing

