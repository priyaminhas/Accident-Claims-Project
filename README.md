# Accident-Claims-Project
Accident Claims Project



## State Diagram
<img src='./Copy of cliam_settlement.png' />


## State Data

1.	States :
a.	No Claim
b.	Claim Filed
c.	Claim Settled
2.	State: 0
3.	Policy number: ‘’
4.	Make: ‘’
5.	Model: ‘’ 
6.	Year: ‘’
7.	Registration: ‘’
8.	License Plate Number: ‘’
9.	Date of Accident: ‘’
10.	Time of Accident: ‘’
11.	Location of Accident: ‘’
12.	Extent of Injuries: ‘’
13.	Accident Description: ‘’
14.	Name of Accident Driver: ‘’
15.	License of Accident Driver: ‘’

## Functions and Transitions
### Transitions

1.	FileAccidentReport(above state data needed)
2.	FaultDeterminationFunction()
3.	DisagreeClaimReviseDecision()
4.	RefusalToRevise()

### Functions

1.	CheckClaim()
2.	CheckStatus()

### Roles

1.	FileAccidentReport(above state data needed) -> Claimant
2.	FaultDeterminationFunction() -> Insurance Company
3.	DisagreeClaimReviseDecision() -> Claimant
4.	RefusalToRevise() -> Insurance Company
