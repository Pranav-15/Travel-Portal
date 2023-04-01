Travel Portal Requirements
1. Every employee must be able to log the trip expenses in the following categories
	a. Transpostation
	b. Communication
	c. Food
	d. Accommodation
	e. Visa Application
	f. Others
2. Should be able to generate a voucher when bill is not available.
3. Should be able to upload bill image from camera of phone or files from desktop.
4. Should have roles heirarchy so that travel expense can be approved at different levels based on total trip expense.
5. Should be able to log expenses in multiple currencies.
6. Finance should be able view entire trip and log advance if any against the trip and then calulate the final settlement.
7. Rao Sir should be able to sign on the voucher digitally.


Architecture
Employee Info
- Employee ID
- Name
- Rate Role
- Reporting Employee ID
- Email ID
- Phone Number
- Bank Name
- Bank Account Number
- IFSC Code
- Password


Rate Role
- Name of Rate Role
- Daily allowance with food
- Daily allowance without food


Trip
- Trip ID
- Start Date
- End Date
- Trip Type
- Employee ID
- Vouchers
- Images


Voucher
a. Transpostation
b. Communication
c. Food
d. Accommodation
e. Visa Application
f. Others